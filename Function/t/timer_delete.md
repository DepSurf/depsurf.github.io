# Function: <code>timer_delete</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int timer_delete(struct timer_list * timer)
```

```json
{
  "name": "timer_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774640,
      "name": "timer_delete",
      "external": true,
      "loc": "kernel/time/timer.c:1359",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
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
      "addr": 18446744071580774640,
      "name": "timer_delete",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int timer_delete(struct timer_list * timer)
```

```json
{
  "name": "timer_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857712,
      "name": "timer_delete",
      "external": true,
      "loc": "kernel/time/timer.c:1359",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
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
      "addr": 18446744071580857712,
      "name": "timer_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int timer_delete(struct timer_list * timer)
```

```json
{
  "name": "timer_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947872,
      "name": "timer_delete",
      "external": true,
      "loc": "kernel/time/timer.c:1359",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
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
      "addr": 18446744071580947872,
      "name": "timer_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int timer_delete(struct timer_list * timer)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
