# Function: <code>refcount_inc_not_zero_checked</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965504,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:118",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965504,
      "name": "refcount_inc_not_zero_checked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145376,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145376,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584267824,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267824,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496151232,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:get_wchan",
        "arch/arm64/kernel/stacktrace.c:__save_stack_trace",
        "arch/arm64/kernel/traps.c:dump_backtrace",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:get_pi_state",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_set_output",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_lock_task_context",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/crypto/keyring.c:add_master_key",
        "fs/posix_acl.c:get_cached_acl",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_open_net",
        "fs/configfs/item.c:config_item_get_unless_zero",
        "fs/debugfs/file.c:debugfs_file_get",
        "ipc/util.c:ipc_rcu_getref",
        "security/keys/key.c:key_lookup",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:rawdata_open",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_profile_hash_show",
        "security/apparmor/apparmorfs.c:seq_profile_attach_show",
        "security/apparmor/apparmorfs.c:seq_profile_mode_show",
        "security/apparmor/apparmorfs.c:seq_profile_name_show",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_find_child",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_task_setrlimit",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_sb_umount",
        "security/apparmor/lsm.c:apparmor_sb_mount",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "block/bsg-lib.c:bsg_job_get",
        "lib/refcount.c:refcount_inc_checked",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/hvc/hvc_console.c:hvc_get_by_index",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/edac/ghes_edac.c:ghes_edac_register",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/filter.c:sk_filter_charge",
        "net/core/fib_rules.c:fib_rules_lookup",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/inetpeer.c:lookup",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/tcp_input.c:inet_reqsk_alloc",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_doi_getdef",
        "net/ipv6/inet6_hashtables.c:inet6_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496151232,
      "name": "refcount_inc_not_zero_checked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472100,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:get_pi_state",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_set_output",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_lock_task_context",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/crypto/keyring.c:add_master_key",
        "fs/posix_acl.c:get_cached_acl",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_open_net",
        "fs/configfs/item.c:config_item_get_unless_zero",
        "fs/debugfs/file.c:debugfs_file_get",
        "ipc/util.c:ipc_rcu_getref",
        "security/keys/key.c:key_lookup",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:rawdata_get_link_base",
        "security/apparmor/apparmorfs.c:rawdata_open",
        "security/apparmor/apparmorfs.c:seq_rawdata_open",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_profile_hash_show",
        "security/apparmor/apparmorfs.c:seq_profile_attach_show",
        "security/apparmor/apparmorfs.c:seq_profile_mode_show",
        "security/apparmor/apparmorfs.c:seq_profile_name_show",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_find_child",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_task_setrlimit",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_sb_umount",
        "security/apparmor/lsm.c:apparmor_sb_mount",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "block/bsg-lib.c:bsg_job_get",
        "lib/refcount.c:refcount_inc_checked",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/hvc/hvc_console.c:hvc_get_by_index",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/filter.c:sk_filter_charge",
        "net/core/fib_rules.c:fib_rules_lookup",
        "net/core/sock_map.c:sock_map_link",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/inetpeer.c:lookup",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/tcp_input.c:inet_reqsk_alloc",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_doi_getdef",
        "net/ipv6/inet6_hashtables.c:inet6_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472100,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290411312,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290411312,
      "name": "refcount_inc_not_zero_checked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275204804,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275204804,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236560,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236560,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171760,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171760,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220320,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220320,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool refcount_inc_not_zero_checked(refcount_t * r)
```

```json
{
  "name": "refcount_inc_not_zero_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325152,
      "name": "refcount_inc_not_zero_checked",
      "external": true,
      "loc": "lib/refcount.c:121",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/refcount.c:refcount_inc_checked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325152,
      "name": "refcount_inc_not_zero_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool refcount_inc_not_zero_checked(refcount_t * r)
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
