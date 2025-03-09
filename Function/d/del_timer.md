# Function: <code>del_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813024,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1020",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_insert_request",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/wakeup.c:__pm_stay_awake",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813024,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843440,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1161",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:__pm_stay_awake",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843440,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867840,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1171",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:__pm_stay_awake",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867840,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579881904,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1146",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881904,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925120,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1184",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925120,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579972032,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1192",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972032,
      "name": "del_timer",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580018688,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1191",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018688,
      "name": "del_timer",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062944,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1186",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062944,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112000,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112000,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580172976,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1202",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_destroy",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172976,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580158016,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1196",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_destroy",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158016,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580162496,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1198",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_destroy",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162496,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307200,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1198",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_destroy",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307200,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519184,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1251",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_destroy",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519184,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "del_timer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579977536,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580400485,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811963,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427314,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:laptop_sync_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367737,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589703802,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589774715,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:poke_blanked_console"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589916133,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/serial/kgdb_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590412802,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591558726,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591721557,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591758165,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591882044,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592110015,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593107789,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593361814,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593864288,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594553733,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594613250,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594707742,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594774615,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594982692,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595092160,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595252924,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595288805,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
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
  "name": "del_timer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580026576,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469107,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895163,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632514,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:laptop_sync_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643737,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590008434,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590079643,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:poke_blanked_console"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225301,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/tty/serial/kgdb_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590732338,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591980477,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592144949,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592181461,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592305404,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592533759,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593556285,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593825459,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594239229,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594945557,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595005202,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595103038,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595169798,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595376487,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595485895,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595648300,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595687269,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
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
  "name": "del_timer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059424,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580528899,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811067,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:nocb_gp_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985595,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803746,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:laptop_sync_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588944137,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590346946,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress",
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590418843,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:poke_blanked_console"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590566037,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/tty/serial/kgdb_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591094258,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592720413,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592885477,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592922181,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593046748,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593278239,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594332989,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594607011,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595036532,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595757909,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595817874,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595915710,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596012902,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy",
        "net/xfrm/xfrm_policy.c:xfrm_policy_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596217623,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596328519,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_run_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596495756,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596535029,
      "name": "del_timer",
      "external": false,
      "loc": "include/linux/timer.h:196",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491330528,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491330528,
      "name": "del_timer",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225320016,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/mmc/host/sdhci.c:sdhci_del_timer",
        "drivers/mmc/host/sdhci.c:sdhci_del_timer",
        "sound/core/timer.c:snd_timer_s_stop",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225320016,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284254000,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284254000,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271827434,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "net/core/sock.c:sk_stop_timer",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271827434,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081200,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081200,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026016,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026016,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072272,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netfilter/nfnetlink_log.c:__nfulnl_flush",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_net",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_destroy",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072272,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int del_timer(struct timer_list * timer)
```

```json
{
  "name": "del_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580123136,
      "name": "del_timer",
      "external": true,
      "loc": "kernel/time/timer.c:1190",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread",
        "mm/page-writeback.c:laptop_sync_completion",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_shutdown",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123136,
      "name": "del_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int del_timer(struct timer_list * timer)
```
</details>
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
