# Function: <code>dump_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946144,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:26",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle_task.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc_failed",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/scsi/hosts.c:scsi_register",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "net/core/gen_estimator.c:gen_estimator_active",
        "net/core/dev.c:__dev_getfirstbyhwtype",
        "net/core/dev.c:__dev_get_by_flags",
        "net/core/dev.c:netdev_has_upper_dev",
        "net/core/dev.c:netdev_master_upper_dev_get",
        "net/core/dev.c:dev_get_nest_level",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:netdev_rx_handler_register",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:netif_set_real_num_rx_queues",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:dev_set_alias",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_run_todo",
        "net/core/ethtool.c:__ethtool_get_settings",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_rules_event",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/ipv4/devinet.c:inet_hash_remove",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_ifa_byprefix",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/igmp.c:ip_mc_inc_group",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:igmp_netdev_event",
        "net/ipv4/igmp.c:ip_mc_dec_group",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_unmap",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_init_dev",
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_destroy_dev",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/addrconf.c:ipv6_find_idev",
        "net/ipv6/addrconf.c:addrconf_add_dev",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_dev_mc_dec",
        "net/8021q/vlan_core.c:vlan_uses_dev",
        "net/8021q/vlan_core.c:vlan_vid_del",
        "net/8021q/vlan_core.c:vlan_vids_del_by_dev",
        "net/8021q/vlan_core.c:vlan_vid_add",
        "net/8021q/vlan_core.c:vlan_vids_add_by_dev",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946144,
      "name": "dump_stack",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233391,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:26",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle_task.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:warn_alloc_failed",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/scsi/hosts.c:scsi_register",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "net/core/gen_estimator.c:gen_estimator_active",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:dev_get_nest_level",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:netdev_master_upper_dev_get",
        "net/core/dev.c:netdev_has_upper_dev",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netdev_rx_handler_register",
        "net/core/dev.c:netdev_is_rx_handler_busy",
        "net/core/dev.c:netif_set_real_num_rx_queues",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:dev_set_alias",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_get_by_flags",
        "net/core/dev.c:__dev_getfirstbyhwtype",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_rules_event",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/devinet.c:inet_ifa_byprefix",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:inet_hash_remove",
        "net/ipv4/igmp.c:igmp_netdev_event",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_destroy_dev",
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_init_dev",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_unmap",
        "net/ipv4/igmp.c:ip_mc_dec_group",
        "net/ipv4/igmp.c:ip_mc_inc_group",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/addrconf.c:addrconf_add_dev",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_find_idev",
        "net/ipv6/mcast.c:ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/8021q/vlan_core.c:vlan_uses_dev",
        "net/8021q/vlan_core.c:vlan_vids_del_by_dev",
        "net/8021q/vlan_core.c:vlan_vids_add_by_dev",
        "net/8021q/vlan_core.c:vlan_vid_del",
        "net/8021q/vlan_core.c:vlan_vid_add",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/switchdev/switchdev.c:switchdev_port_fwd_mark_set",
        "net/switchdev/switchdev.c:switchdev_get_dev_by_nhs",
        "net/switchdev/switchdev.c:call_switchdev_notifiers",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233391,
      "name": "dump_stack",
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348639,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:26",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle_task.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/scsi/hosts.c:scsi_register",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:dev_get_nest_level",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:netdev_master_upper_dev_get",
        "net/core/dev.c:netdev_has_upper_dev",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netdev_rx_handler_register",
        "net/core/dev.c:netdev_is_rx_handler_busy",
        "net/core/dev.c:netif_set_real_num_rx_queues",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:dev_set_alias",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_get_by_flags",
        "net/core/dev.c:__dev_getfirstbyhwtype",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_rules_event",
        "net/sched/sch_generic.c:pfifo_fast_reset",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/sch_fifo.c:qdisc_reset_queue",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/devinet.c:inet_ifa_byprefix",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:inet_hash_remove",
        "net/ipv4/igmp.c:igmp_netdev_event",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_destroy_dev",
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_init_dev",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_unmap",
        "net/ipv4/igmp.c:ip_mc_dec_group",
        "net/ipv4/igmp.c:ip_mc_inc_group",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/addrconf.c:addrconf_add_dev",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_find_idev",
        "net/ipv6/mcast.c:ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/8021q/vlan_core.c:vlan_uses_dev",
        "net/8021q/vlan_core.c:vlan_vids_del_by_dev",
        "net/8021q/vlan_core.c:vlan_vids_add_by_dev",
        "net/8021q/vlan_core.c:vlan_vid_del",
        "net/8021q/vlan_core.c:vlan_vid_add",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/switchdev/switchdev.c:call_switchdev_notifiers",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348639,
      "name": "dump_stack",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588200261,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:27",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle_task.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/scsi/hosts.c:scsi_register",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:dev_get_nest_level",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:netdev_master_upper_dev_get",
        "net/core/dev.c:netdev_has_any_upper_dev",
        "net/core/dev.c:netdev_has_upper_dev",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netdev_is_rx_handler_busy",
        "net/core/dev.c:netif_set_real_num_rx_queues",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:dev_set_alias",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_get_by_flags",
        "net/core/dev.c:__dev_getfirstbyhwtype",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:__ethtool_get_link_ksettings",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_rules_event",
        "net/sched/sch_generic.c:pfifo_fast_reset",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/cls_api.c:tcf_exts_change",
        "net/sched/sch_fifo.c:qdisc_reset_queue",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/devinet.c:inet_ifa_byprefix",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:inet_hash_remove",
        "net/ipv4/igmp.c:igmp_netdev_event",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_destroy_dev",
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_init_dev",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_unmap",
        "net/ipv4/igmp.c:ip_mc_dec_group",
        "net/ipv4/igmp.c:ip_mc_inc_group",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_dev_config",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/addrconf.c:addrconf_add_dev",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_find_idev",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/8021q/vlan_core.c:vlan_uses_dev",
        "net/8021q/vlan_core.c:vlan_vids_del_by_dev",
        "net/8021q/vlan_core.c:vlan_vids_add_by_dev",
        "net/8021q/vlan_core.c:vlan_vid_del",
        "net/8021q/vlan_core.c:vlan_vid_add",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_deferred_process",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588200261,
      "name": "dump_stack",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588749109,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:28",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle_task.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/bpf/offload.c:bpf_offload_notification",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/scsi/hosts.c:scsi_register",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:netdev_lower_state_changed",
        "net/core/dev.c:dev_get_nest_level",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:netdev_master_upper_dev_get",
        "net/core/dev.c:netdev_has_any_upper_dev",
        "net/core/dev.c:netdev_has_upper_dev",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netdev_is_rx_handler_busy",
        "net/core/dev.c:netif_set_real_num_rx_queues",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:__dev_get_by_flags",
        "net/core/dev.c:__dev_getfirstbyhwtype",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:__ethtool_get_link_ksettings",
        "net/core/dev_addr_lists.c:dev_addr_del",
        "net/core/dev_addr_lists.c:dev_addr_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_rules_event",
        "net/core/fib_rules.c:fib_rules_seq_read",
        "net/sched/sch_generic.c:pfifo_fast_reset",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/cls_api.c:tcf_exts_destroy",
        "net/sched/sch_fifo.c:qdisc_reset_queue",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/devinet.c:inet_ifa_byprefix",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:inet_hash_remove",
        "net/ipv4/igmp.c:igmp_netdev_event",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group",
        "net/ipv4/igmp.c:ip_mc_join_group",
        "net/ipv4/igmp.c:ip_mc_destroy_dev",
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_init_dev",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_unmap",
        "net/ipv4/igmp.c:ip_mc_dec_group",
        "net/ipv4/igmp.c:ip_mc_inc_group",
        "net/ipv4/fib_notifier.c:fib4_seq_read",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:ipmr_seq_read",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:call_ipmr_mfc_entry_notifiers",
        "net/ipv4/ipmr.c:call_ipmr_vif_entry_notifiers",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_dev_config",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/addrconf.c:addrconf_add_dev",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_find_idev",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/8021q/vlan_core.c:vlan_uses_dev",
        "net/8021q/vlan_core.c:vlan_vids_del_by_dev",
        "net/8021q/vlan_core.c:vlan_vids_add_by_dev",
        "net/8021q/vlan_core.c:vlan_vid_del",
        "net/8021q/vlan_core.c:vlan_vid_add",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_deferred_process",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588749109,
      "name": "dump_stack",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126973,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/dma/swiotlb.c:swiotlb_alloc",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126973,
      "name": "dump_stack",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589361654,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_alloc_base_nid",
        "mm/memblock.c:memblock_alloc_range",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361654,
      "name": "dump_stack",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589818758,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818758,
      "name": "dump_stack",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590045030,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045030,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585039043,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_reenter_check",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_slow",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585039043,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591381443,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:90",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmalloc_fix_flags",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_slow",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381443,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591323835,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:90",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmalloc_fix_flags",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323835,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592341941,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:111",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmalloc_fix_flags",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/ubsan.c:ubsan_epilogue",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/neighbour.c:neigh_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341941,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594203537,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:111",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/module/main.c:do_init_module",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_reenter_check",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmalloc_fix_flags",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/ubsan.c:ubsan_epilogue",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_copy_abs",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/neighbour.c:neigh_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203537,
      "name": "dump_stack",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595753040,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:111",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add",
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/module/main.c:do_init_module",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_reenter_check",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/dev.c:netdev_rx_csum_fault",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_add_timer",
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "lib/kobject.c:kobject_add",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595753040,
      "name": "dump_stack",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596277088,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:111",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add",
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/module/main.c:do_init_module",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_reenter_check",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/gup.c:gup_vma_lookup",
        "mm/memory.c:print_bad_pte",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "mm/migrate.c:alloc_misplaced_dst_folio",
        "fs/buffer.c:__getblk_slow",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte",
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_add_timer",
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596277088,
      "name": "dump_stack",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597161776,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:111",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add",
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:__warn_flushing_systemwide_wq",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/module/main.c:do_init_module",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_reenter_check",
        "kernel/debug/debug_core.c:kdb_dump_stack_on_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmalloc_fix_flags",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/gup.c:gup_vma_lookup",
        "mm/memory.c:print_bad_pte",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:__kmalloc_large_node",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/migrate.c:alloc_misplaced_dst_folio",
        "fs/buffer.c:__getblk_slow",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/super.c:ext4_destroy_inode",
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte",
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/input/input.c:input_set_capability",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_add_timer",
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597161776,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503806792,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/of/dynamic.c:of_node_release",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503806792,
      "name": "dump_stack",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236429352,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/process.c:show_regs",
        "arch/arm/kernel/traps.c:__div0",
        "arch/arm/kernel/fiq.c:release_fiq",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/plat-omap/dma.c:omap_dma_link_lch",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_slow",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/of/dynamic.c:of_node_release",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236429352,
      "name": "dump_stack",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297645948,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending",
        "arch/powerpc/kernel/watchdog.c:wd_lockup_ipi",
        "arch/powerpc/platforms/pseries/iommu.c:tce_get_pSeriesLP",
        "arch/powerpc/platforms/pseries/iommu.c:tce_free_pSeriesLP",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_stuff_tce",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_tce_iommu_map",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_tce_iommu_map",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_tce_put",
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/of/dynamic.c:of_node_release",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297645948,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279703110,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/input/input.c:input_set_capability",
        "drivers/of/dynamic.c:of_node_release",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279703110,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647286,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647286,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589373158,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373158,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090662,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090662,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dump_stack()
```

```json
{
  "name": "dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590140918,
      "name": "dump_stack",
      "external": true,
      "loc": "lib/dump_stack.c:88",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/workqueue.c:process_one_work",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/module.c:do_init_module",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/oom_kill.c:dump_header",
        "mm/percpu.c:pcpu_alloc",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:bad_page",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:slab_err",
        "mm/slub.c:print_trailer",
        "fs/buffer.c:__getblk_gfp",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "fs/ext4/inode.c:ext4_write_inode",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/core/dev.c:netdev_run_todo",
        "net/core/neighbour.c:neigh_destroy",
        "lib/kobject.c:kobject_add",
        "lib/kobject.c:kobject_init",
        "lib/kobject.c:kobject_init",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140918,
      "name": "dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
