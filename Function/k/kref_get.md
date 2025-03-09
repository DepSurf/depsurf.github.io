# Function: <code>kref_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366242,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579493005,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650483,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746576,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869620,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995563,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015392,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021968,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ]
    },
    {
      "addr": 18446744071580143846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580412479,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789859,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307239,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442282,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582081690,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/file.c:fuse_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100555,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471536,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478229,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478944,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_get_task_label",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_restore_previous_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489552,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile"
      ],
      "caller_func": [
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile"
      ]
    },
    {
      "addr": 18446744071582511696,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:aa_setup_default_label",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_lookupn_profile",
        "security/apparmor/policy.c:aa_lookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_may_open_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629275,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071582526710,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582529472,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545383,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551153,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582554478,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_alloc_proxy",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582599434,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582868950,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955174,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129813,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583163296,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378620,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580782,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583959757,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:get_current_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:tty_find_polling_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002858,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382202,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008761,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584187417,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195805,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584478257,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584714661,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584764998,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832884,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584878445,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584894332,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157844,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187437,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585202041,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_get_from_anchor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585214482,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231796,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586090155,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193674,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587329947,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021968,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582489552,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582629275,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582529472,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374872,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579507003,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667657,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768864,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898964,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027616,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580048146,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055445,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ]
    },
    {
      "addr": 18446744071580067999,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177974,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580484894,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913108,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473607,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624868,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308555,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316315,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582698484,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:rawdata_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710343,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713439,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_get_task_label",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743550,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile"
      ]
    },
    {
      "addr": 18446744071582757496,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_setup_default_label",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878715,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071582764922,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582769959,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785854,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582791817,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813848,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823634,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582844252,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154182,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242758,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583424281,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583460041,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693703,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902945,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305637,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:get_current_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334250,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584336734,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584340055,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526642,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534989,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584823881,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585055009,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065605,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585122274,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585124185,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/fence-array.c:fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585124660,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585195903,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585240781,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585256796,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558896,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579549,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597302,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607898,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585625249,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586106578,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586501115,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648778,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587828299,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054544,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582722480,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582878715,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582768064,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579393890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579527675,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579692249,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795820,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930900,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061645,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087586,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580095260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ]
    },
    {
      "addr": 18446744071580108223,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218518,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580546014,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580981700,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554295,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713156,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396887,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404661,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792196,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:rawdata_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582804935,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808031,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_get_task_label",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838855,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile"
      ]
    },
    {
      "addr": 18446744071582852671,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_setup_default_label",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975807,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071582860202,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865319,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881246,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887449,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909620,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582940252,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265097,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583358070,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549769,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587769,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583831815,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043442,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584307819,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584487690,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:get_current_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584516106,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584518574,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584521895,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584708770,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584717117,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585017289,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585238293,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585250245,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309897,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585311602,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585315983,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585317906,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390623,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440605,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456478,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585746576,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585767197,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784870,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585795466,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585812865,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586307464,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855319,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588043227,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:40",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094400,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582817136,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582975807,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582863424,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380110,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579515239,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688841,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792834,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938830,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066994,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093746,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100220,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580113515,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225776,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580573244,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580816601,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028937,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283676,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540905,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608316,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767360,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481530,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488388,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883510,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582894702,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896024,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_get_task_label",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919970,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582929534,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932868,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937778,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948457,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951193,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956751,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582959014,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971739,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978637,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583319275,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587569,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628437,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583874358,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102303,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584386621,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584487805,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584568037,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584594666,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597822,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599225,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604242,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584790713,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799037,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585102964,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585320550,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585332409,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585398833,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585399559,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585401789,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405458,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475487,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585523506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540655,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833694,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853105,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871302,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585881725,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585899801,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586406144,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011951,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588207157,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588208291,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579408314,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579541803,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719769,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826486,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579984241,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580119340,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146818,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580153721,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ]
    },
    {
      "addr": 18446744071580166059,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280448,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580654124,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580906745,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138424,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423196,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683707,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752364,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916992,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017037,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632444,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582639588,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042935,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052994,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054741,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_get_task_label",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context",
        "security/apparmor/context.c:aa_dup_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079306,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile"
      ]
    },
    {
      "addr": 18446744071583089742,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095386,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583098034,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104265,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113651,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583119273,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121206,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135783,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142525,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583503371,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833497,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874629,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584137991,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373755,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584898984,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584980122,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585006714,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585010238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585012073,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017762,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585210972,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219389,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585528856,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748467,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585760457,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585827029,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585828023,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831709,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585836016,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585906623,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585956409,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972403,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586273070,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586292929,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586322189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586340585,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586872626,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057224,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_add",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588548831,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588756591,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588757846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155269,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583062864,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583090768,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583099264,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579423094,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579569497,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752457,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860286,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580035617,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580178728,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206626,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213193,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225930,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341581,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580782012,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042953,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278790,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581100,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848224,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920860,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101424,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205453,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826015,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867250,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244462,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255614,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281452,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583292814,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583295242,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583301686,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310582,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583318743,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324578,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326880,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341653,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348351,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584033993,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075205,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354646,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584596437,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022705,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130312,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585196708,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585213681,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585240890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585244366,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246249,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251933,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446867,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456253,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585656730,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585769730,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585994419,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586006645,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073168,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073911,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586078797,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083034,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153599,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586202329,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220517,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586231077,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586530622,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586550477,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568998,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579514,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586598059,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587166044,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587355640,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_add",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135359,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135990,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293856,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583303040,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579455146,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579606608,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795321,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907214,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082433,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580226792,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258882,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265849,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580278334,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397453,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848820,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120105,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361334,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935441,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582005228,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195760,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300461,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582928610,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936437,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975474,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583358560,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583371633,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373349,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400343,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411182,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413722,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583420178,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429160,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583437714,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443133,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445440,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583460052,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583466991,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584116729,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584159781,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584449718,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692373,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130209,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585241112,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585313428,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585332625,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585360298,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363790,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585365657,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371357,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585570275,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579517,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585788875,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585903470,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586131267,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144213,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586215261,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586217904,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586221687,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223069,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586227306,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295151,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345113,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586361045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586371493,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571754,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679198,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586699325,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586718214,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586728605,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586747179,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587270149,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587345997,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587535080,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587785363,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589370207,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589370838,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:45",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411920,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583421536,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579473159,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630910,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823866,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858343,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579942519,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580125969,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/time/posix-clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-clock.c:posix_clock_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272565,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580309890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580316719,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328302,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450221,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952018,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184718,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471892,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740705,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784412,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073232,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141816,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360393,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466797,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107097,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116709,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156498,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583545296,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558698,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583560348,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586992,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597088,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599402,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583605953,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583614633,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583622781,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628327,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630459,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636058,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651443,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584305685,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349962,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584646341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584892887,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585336568,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585453370,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585526301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585545240,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585573882,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585577503,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579320,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585585101,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585788930,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799630,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586002541,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586019867,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586143081,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586365876,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586379669,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447912,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586457533,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586460236,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461705,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586464783,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/reservation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586466718,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586471076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586538559,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588619,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586604490,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586615189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586823156,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586932750,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586954225,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586973353,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586983015,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587539573,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616906,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809013,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588089500,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589827249,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589827686,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597824,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583607264,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579499265,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656462,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872138,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906887,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579992695,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319585,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358722,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365551,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580377102,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580499181,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004802,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581242565,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536148,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581856640,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153060,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582219016,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582459257,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565741,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583212585,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583222410,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262562,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650976,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664426,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693211,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703248,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705562,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583712129,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583720809,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583728957,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734503,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583736635,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742346,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757731,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584440357,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484513,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584784069,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028631,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475256,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585593911,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585667392,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585686152,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585718415,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720232,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585726013,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931666,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942318,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586149709,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586168184,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586291561,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586513924,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586595880,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605197,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586607580,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609161,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612639,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586614606,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586618868,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586686687,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586736059,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586751930,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586762629,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586969252,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044752,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587062946,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131182,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587152929,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587172393,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587182055,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587201757,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587742357,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588014181,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588246337,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295331,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590053457,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590053830,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703984,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583713440,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579528095,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688776,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722245,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:create_new_namespaces"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914330,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948115,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580039858,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580263055,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:timens_on_fork",
        "kernel/time/namespace.c:timens_install",
        "kernel/time/namespace.c:timens_install",
        "kernel/time/namespace.c:timens_for_children_get",
        "kernel/time/namespace.c:timens_get",
        "kernel/time/namespace.c:copy_time_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392152,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580431904,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580439557,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452240,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584560,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033256,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:init_seq_pidns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181415,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255281,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431714,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744847,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082918,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582456104,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754876,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582873733,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540575,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583552742,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590374,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011563,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584025586,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584027937,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059467,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072400,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:update_to_newest_parent",
        "security/apparmor/policy.c:update_to_newest_parent",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584081157,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084451,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609280405,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584110534,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117580,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120776,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_find_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129973,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147420,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585003125,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048295,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049188,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585150465,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475817,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585729697,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194937,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586316862,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586392238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586414067,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445921,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448159,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586450138,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456749,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662579,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:find_port_by_devt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586684602,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_attr_current_show",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586907001,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586927938,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587061178,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587294826,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587309237,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382656,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393773,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587395377,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397209,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401518,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409208,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413486,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587485654,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587539778,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556865,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587597749,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876532,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_name",
        "drivers/vfio/vfio.c:vfio_device_get_from_name",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu",
        "drivers/vfio/vfio.c:vfio_create_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587902853,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587973102,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003773,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588022633,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588032791,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054151,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:init_usb_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588876191,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123200,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589176562,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579261368,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579510459,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907802,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580023042,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580440800,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574064,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297329,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474386,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792623,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130583,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441169,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512677,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582946789,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650389,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669197,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584132011,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145010,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147393,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178576,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584191808,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195834,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203811,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612349237,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229622,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584236540,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239560,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584248356,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584265804,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585123861,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198119,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198980,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585301777,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617577,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851857,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293140,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586435486,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586507374,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586529715,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560225,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562639,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586564618,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571085,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586772499,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:find_port_by_devt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586792635,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586991929,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587011842,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587145678,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356122,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371269,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587449582,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587462029,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463617,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587465785,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587468686,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587477736,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587483214,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587553238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587605663,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624833,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663893,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936996,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_name",
        "drivers/vfio/vfio.c:vfio_device_get_from_name",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu",
        "drivers/vfio/vfio.c:vfio_create_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587963445,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588032846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588056445,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588068677,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588082723,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099639,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:init_usb_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588884879,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121232,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589172098,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579263797,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579513765,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579916762,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947068,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580023746,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580444880,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580577952,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314897,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494802,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820623,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155351,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468203,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540453,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582974277,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583670957,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690237,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158507,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584172067,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584174529,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205581,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218704,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584222714,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230402,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614490194,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254678,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261596,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584264568,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584271268,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291193,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585004421,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585081255,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585082052,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185777,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585496025,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585730544,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187849,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586319630,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586391790,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586415514,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445185,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447599,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586449562,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586455869,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664137,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586673035,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872804,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586895134,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587032774,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587237961,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587253285,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587331262,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342525,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587345566,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347705,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350558,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359752,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364398,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435656,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587486863,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506043,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587543621,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729622,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818084,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu",
        "drivers/vfio/vfio.c:vfio_create_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845850,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914270,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587939117,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587951461,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587965523,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587981981,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588772479,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589011072,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589065810,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579305045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579585330,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038762,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156002,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609792,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580748032,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560145,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754306,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107977,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856565,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583309877,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584030003,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584048338,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542507,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584556793,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584559473,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584590814,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604144,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608154,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616050,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615437156,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640454,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647548,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650520,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584657300,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677324,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585445525,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585527431,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585528996,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585639678,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963016,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586212456,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586689625,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586839342,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918532,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586942522,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586971617,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586973839,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586976506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982909,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587212297,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221275,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587457157,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599943,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587804249,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587898126,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587905926,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_excl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587908957,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587911950,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914121,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587916894,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926680,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931374,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588009176,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063055,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588083851,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588122389,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588323110,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588421812,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu",
        "drivers/vfio/vfio.c:vfio_create_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588524158,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588549501,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588562101,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588576598,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588594717,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589464447,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725664,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589784290,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579362893,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676670,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:vm_area_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580209730,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580301670,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580815164,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962128,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912681,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582139341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483202,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_update_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550928,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993758,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419221,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583816961,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584618388,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637680,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191377,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585199846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203297,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585237649,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585253214,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585256522,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585267728,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617234640,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_current_getsecid_subj",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_init_security",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585296830,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585304630,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585308010,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_unconfined",
        "security/apparmor/policy_ns.c:alloc_unconfined"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585318114,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy",
        "security/apparmor/label.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585336579,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586586917,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586680279,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586682835,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586800571,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587167979,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587449861,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587961425,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124130,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211419,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588236439,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267807,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588270318,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588273335,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281389,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518817,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588527606,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588776084,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588938044,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589152695,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589169285,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247768,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254200,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589259019,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263411,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265722,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589270622,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589281236,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285086,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589369433,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453985,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503141,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589716469,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589816883,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_set_container"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589932189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589960429,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589972709,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589988327,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590006532,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590942147,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591234304,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591295744,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433853,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796907,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:vm_area_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402402,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580513846,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101436,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256608,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582347737,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616813,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997916,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_update_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067163,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266535,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:init_node_memory_type",
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583555246,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006789,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584438881,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585097718,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297908,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585318238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585920337,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585930107,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_dup_audit_data",
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931492,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585935041,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971565,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987070,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585990634,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627947017,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_current_getsecid_subj",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_init_security",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586034130,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586044155,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627947629,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_find_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586058114,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy",
        "security/apparmor/label.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586077247,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586098683,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy",
        "security/apparmor/notify.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587827269,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936987,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588380827,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710341,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589322833,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511330,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589619515,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589647042,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589682527,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589685158,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589697117,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961265,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589971514,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590269297,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590452380,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590703191,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721477,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590807268,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590814872,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590821339,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590825507,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590827962,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590829787,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590834366,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590842550,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590846862,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590918499,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590939400,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591031761,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591087333,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591333685,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591513677,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591550077,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591566037,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591583010,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591606436,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592644051,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593046639,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595760615,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595763555,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579445901,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845130,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:vm_area_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580471184,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586477,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193116,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351712,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550617,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582825549,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583205850,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_update_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277694,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486887,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:init_node_memory_type",
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771707,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584232517,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584667649,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327289,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585528247,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548172,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152545,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163181,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find",
        "security/apparmor/audit.c:aa_dup_audit_data",
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163963,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167409,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586202954,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219550,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223722,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586235357,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619709550,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_current_getsecid_subj",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_init_security",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269378,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586279195,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619710893,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_find_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293122,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy",
        "security/apparmor/label.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586312528,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586336970,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_clone_ruleset",
        "security/apparmor/notify.c:aa_clone_ruleset",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy",
        "security/apparmor/notify.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100405,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211227,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588656831,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998565,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589620945,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589812290,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923043,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950912,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589987135,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589989766,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590001805,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590270625,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590281114,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590589636,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590772620,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591044263,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591062725,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591148541,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591155944,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163035,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591167323,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591170024,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591171793,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176590,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591184617,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189406,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591261891,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591283176,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591385836,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591444117,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591695205,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591935053,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591971709,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591987797,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592004805,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028244,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593074547,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593499119,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596284967,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596287955,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579475660,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882964,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:vm_area_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531008,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580650829,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299404,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457680,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open",
        "kernel/relay.c:relay_create_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721209,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:get_watch_queue",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999997,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441418,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_update_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516814,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583679767,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:init_node_memory_type",
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583973603,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:setup_bdev_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584447349,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584900417,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585561993,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765414,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585786396,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840863,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/tracefs/event_inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "fs/tracefs/event_inode.c:eventfs_root_lookup",
        "fs/tracefs/event_inode.c:eventfs_root_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586401748,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412029,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find",
        "security/apparmor/audit.c:aa_dup_audit_data",
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412811,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418937,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/task.c:aa_profile_ns_perm",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454963,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586472110,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_alloc_null",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476426,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488611,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622017118,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:aa_setup_dfa_engine",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getselfattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_init_security",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586525909,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536062,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622017981,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549810,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy",
        "security/apparmor/label.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586569088,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586603595,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_clone_ruleset",
        "security/apparmor/notify.c:aa_clone_ruleset",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_do_notification",
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy",
        "security/apparmor/notify.c:aa_get_current_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436548,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504027,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588957351,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589302868,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589930888,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148658,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261589,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590289407,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590325647,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590328294,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590340187,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590611505,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590622218,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948355,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591115164,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:assign_fw",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591388775,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591407477,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591494534,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591501880,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591509019,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591513307,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591516008,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591517788,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591522590,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591530649,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591536045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591609187,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591630616,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591736459,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591794293,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591945636,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_auth.c:drm_file_get_master",
        "drivers/gpu/drm/drm_auth.c:drm_master_open",
        "drivers/gpu/drm/drm_auth.c:drm_setmaster_ioctl",
        "drivers/gpu/drm/drm_auth.c:drm_new_set_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592002932,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592071139,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_gem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj",
        "drivers/gpu/drm/drm_gem.c:drm_gem_vm_open",
        "drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl",
        "drivers/gpu/drm/drm_gem.c:objects_lookup",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592097994,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_mode_object.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592135158,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_prime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap",
        "drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_export"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592157291,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_syncobj.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592226626,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_atomic_helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592259729,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/gpu/drm/drm_gem_atomic_helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592438229,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592675485,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592711549,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592727717,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592744934,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593826467,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594246911,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595936484,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "net/ipv4/tcp_sigpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_sigpool.c:tcp_sigpool_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597169831,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597172819,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490533900,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490589856,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "virt/kvm/arm/vgic/vgic-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490631288,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490829648,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491070972,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491107400,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491182768,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491575948,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491619420,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491626880,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491643000,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491773972,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492348344,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492641108,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492966860,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493326360,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493705324,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493784428,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494074284,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494211248,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494933024,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494949436,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494992444,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495445312,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495457668,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495459344,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495486656,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495496276,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495501320,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495505756,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511043844,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495524960,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495531340,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495533900,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495541640,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495557820,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496326456,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496502716,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497050132,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497440384,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497753276,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498141448,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/soc/qcom/smem_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/smem_state.c:qcom_smem_state_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498260452,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498332688,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498363484,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498406584,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498410132,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498412788,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498419396,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498757720,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498769456,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498943148,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498964136,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499124068,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499396148,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499414664,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499479196,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499489156,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499494840,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499497396,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499500232,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499502944,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499509248,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499592948,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499647136,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499668116,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499687480,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499960616,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500207208,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500230268,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500253096,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500265484,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500285384,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500917604,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501270844,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501282828,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501704260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501816912,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503827588,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503830076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224485328,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224709920,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224860944,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 3225075248,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3225106768,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225206084,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3225539432,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225574616,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 3225581080,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3225595028,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 3225721924,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3226236224,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226483572,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226922708,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 3227232952,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3227298860,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 3227527656,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3227642716,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 3228343048,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 3228352808,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3228405844,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3228811508,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3228824520,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 3228826280,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 3228854244,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3228864064,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3228869316,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3228873332,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3243525460,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3228891644,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 3228897624,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 3228899812,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3228905448,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 3228921032,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229660108,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3229808696,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230577504,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230892816,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/soc/qcom/smem_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/smem_state.c:qcom_smem_state_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3231024992,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 3231049436,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 3231079640,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3231082344,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3231084696,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 3231090456,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 3231377552,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3231385644,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231514568,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231534304,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3231672092,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 3231952076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 3231962144,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 3231966276,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 3231968164,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 3231969540,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 3231973408,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3231978288,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3232050112,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 3232101536,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232118300,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232135648,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3232305500,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/mtd/mtdsuper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/mtdsuper.c:mtd_set_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3232333340,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/mtd/mtd_blkdevs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/mtd_blkdevs.c:blktrans_open",
        "drivers/mtd/mtd_blkdevs.c:blktrans_dev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3232499520,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3232686516,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 3232708644,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 3232726632,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 3232737040,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 3232755612,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233435780,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3233760864,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 3233771516,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3234228432,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3234335720,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3236448792,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 3236450200,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283450956,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283664276,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283952540,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283999280,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284084660,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284558776,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284611244,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284619456,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284639260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284818320,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285599396,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285957780,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286386392,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286865488,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287309716,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287398564,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287736092,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287906200,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288803900,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288816756,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288871488,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289489704,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289508012,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289510412,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289547852,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289561944,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289569532,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289575068,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302718444,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289603712,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289612044,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289615952,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289625472,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289648000,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290645832,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290714076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291517168,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291547960,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291589072,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291594716,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291597012,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291604288,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291921116,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291931748,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292081364,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292109784,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292312720,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292635764,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292656744,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292760860,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292772696,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292778720,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292781984,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292784408,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292790328,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292796996,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292894124,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292970856,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292994044,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293010184,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293286860,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293365756,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293391764,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293494644,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293520736,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293546060,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293563032,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293588120,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294377592,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294792648,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294808168,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295142708,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295214008,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297674740,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297676980,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271386684,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271501412,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271661132,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271685652,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271730840,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271986668,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272019182,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272025388,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272038208,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272091386,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272473796,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272657030,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272876480,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273058016,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273321318,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273376950,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273566460,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273669600,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274239344,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274248076,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274286060,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274635764,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274646240,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274647530,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274671148,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274679524,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274683986,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274687844,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270756046,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274702328,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274707408,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274709710,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274714990,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274728476,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275378238,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275421584,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275898432,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276020314,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276038722,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276064752,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276068240,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276069938,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276075122,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276263284,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276265324,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276327382,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276344918,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276439452,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276628072,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276643380,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276698672,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276707028,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276709418,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276710936,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276711628,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276715554,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276719742,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276783078,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276828452,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276844474,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276854140,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277039654,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277131390,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277150294,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277166986,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277178368,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277195228,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277692742,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277946936,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277956598,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278163802,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279721438,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279722946,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472929,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579632782,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579844314,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878999,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579961431,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288385,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327522,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334351,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580345902,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467981,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973602,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211413,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504884,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825376,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121796,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187752,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427993,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534477,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181321,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191146,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231298,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619712,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583633162,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634812,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661947,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671984,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674298,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583680865,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583689545,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583697693,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703239,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705371,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711082,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726467,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584409093,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584453265,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584732821,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584971015,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585237784,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585356535,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585428416,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585447176,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475914,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585479439,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481256,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585487037,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585692642,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703294,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585910077,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585928552,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586054809,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586204404,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218821,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586286360,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295677,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586298060,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586299641,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586303119,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305086,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586309348,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586377167,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426539,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586442410,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586475379,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_alloc_ns_head"
      ],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_dev_ioctl"
      ]
    },
    {
      "addr": 18446744071586521365,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586837262,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859009,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586878473,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888135,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586907837,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587383301,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639173,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858033,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899091,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589655713,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589656086,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672720,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583682176,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071586482490,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579401841,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561106,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779226,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813991,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579899271,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235761,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274786,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281615,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293070,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414957,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920658,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158149,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447188,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763040,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059236,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125320,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365161,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471645,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118473,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583128298,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168450,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583556768,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583570218,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583571868,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599003,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609040,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583611354,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583617921,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626601,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583634749,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583640295,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583642427,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648138,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663523,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584344293,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584388945,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584663589,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584879815,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189960,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585298464,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585317208,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345930,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585349359,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351176,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585356909,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585552274,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585562494,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585777688,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585900761,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022772,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586037189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586123848,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137053,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586139436,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141017,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144495,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586146462,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586150708,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218479,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302795,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586318666,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586351603,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_alloc_ns_head"
      ],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_dev_ioctl"
      ]
    },
    {
      "addr": 18446744071586389941,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593476,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692672,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586710866,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586779022,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586800497,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819593,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586829255,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848897,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/file.c:usb_register_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587151525,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413045,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587618371,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589381537,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589381910,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583609776,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583619232,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071586358618,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472849,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630046,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867159,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579952967,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279633,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318770,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325599,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580337150,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459229,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964850,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202613,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496196,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816688,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112276,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178232,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418473,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524957,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583165353,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175178,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215330,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583603488,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616938,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618588,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645723,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655760,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658074,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583664641,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673321,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583681469,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687015,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583689147,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694858,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710243,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584392005,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436177,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584734229,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584980215,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585425656,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585544311,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617792,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585636552,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665290,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585668815,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585670632,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585676413,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585881890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892334,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586099725,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586118200,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586240732,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461892,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476309,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586543848,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586553165,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586555548,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586557129,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560607,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562574,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566836,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586634655,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586690619,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706490,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717189,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586923812,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999312,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587017506,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085742,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587107489,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587126953,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136615,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156317,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587698501,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587970325,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588232387,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590099089,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099462,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656496,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583665952,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void kref_get(struct kref * kref)
```

```json
{
  "name": "kref_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579504650,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663882,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579877562,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912553,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579999351,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333953,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580373778,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_install",
        "kernel/utsname.c:utsns_get",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380655,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392382,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_get_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580514893,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025890,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265973,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563588,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581885888,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:set_bdev_super_fc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582185236,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255512,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_ctx_fdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497913,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605629,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_group_find_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258889,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_async_req_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269002,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309218,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700901,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:ns_revision_open",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583714805,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716484,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_set_current_onexec",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583744071,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754272,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756586,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    },
    {
      "addr": 18446744071583763287,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583773749,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_sock_graft",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_socket_post_create",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_sb_pivotroot",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_task_alloc",
        "security/apparmor/lsm.c:apparmor_cred_transfer",
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init"
      ]
    },
    {
      "addr": 18446744071583780943,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583786600,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789035,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:aa_lookupn_ns",
        "security/apparmor/policy_ns.c:aa_findn_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583794333,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:__proxy_share",
        "security/apparmor/label.c:__aa_proxy_redirect",
        "security/apparmor/label.c:aa_alloc_proxy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810731,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584498069,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542305,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584841797,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585086391,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585533576,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_hw_create_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585652279,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725920,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585744680,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_standard_install",
        "drivers/tty/tty_io.c:tty_find_polling_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585773402,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585776911,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_mutex.c:tty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778760,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785549,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_common_install",
        "drivers/tty/pty.c:pty_common_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987618,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:port_fops_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000318,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586208333,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586226808,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586350535,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573588,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587989,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:get_ndd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586655624,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586665163,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586667612,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586669225,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586671919,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586674862,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/sync_file.c:sync_file_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679124,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586747199,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796651,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586812474,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586823157,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030260,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587106480,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_external_user",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_device",
        "drivers/vfio/vfio.c:vfio_group_get_from_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587124674,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587192894,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587214817,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_get_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587234057,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243701,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_set_configuration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587263389,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/usb/core/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587804933,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588085701,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:_find_opp_table_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588318673,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/remoteproc/remoteproc_virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367715,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590149393,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590149926,
      "name": "kref_get",
      "external": false,
      "loc": "include/linux/kref.h:43",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755008,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583764640,
      "name": "kref_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void kref_get(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void kref_get(struct kref * kref)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void kref_get(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void kref_get(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kref_get(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kref_get(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kref_get(struct kref * kref)
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
