# Function: <code>memmove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memmove",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:trace_event_enum_update",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/slub.c:process_slab",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/cfq-iosched.c:cfq_set_prio_slice",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_check_fifo",
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_group_notify_queue_del",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_set_badblocks",
        "drivers/md/md.c:md_set_badblocks",
        "drivers/md/md.c:md_clear_badblocks",
        "drivers/md/md.c:md_clear_badblocks",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003776,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memmove",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_events.c:trace_event_enum_update",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_check_fifo",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_notify_queue_del",
        "block/cfq-iosched.c:cfq_set_prio_slice",
        "lib/vsprintf.c:widen_string",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294160,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memmove",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_events.c:trace_event_enum_update",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/vsprintf.c:widen_string",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412816,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596267892,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:312",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/ftrace.c:ftrace_free_init_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270048,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602583834,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:347",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825744,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602751450,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:348",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203808,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604545509,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:355",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/init.c:init_memory_mapping",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "arch/x86/platform/efi/early_printk.c:early_efi_scroll_up",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/md/md.c:md_ioctl",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589445392,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604639599,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:362",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589903584,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604651887,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590129568,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609002079,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:409",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:eval_replace",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:bpf_adj_linfo_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_merge_regions",
        "mm/memblock.c:memblock_remove_region",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/namei.c:dx_pack_dirents",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/bitmap.c:bitmap_cut",
        "lib/lz4/lz4_compress.c:LZ4_saveDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:lzma2_lzma",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "lib/kobject_uevent.c:zap_modalias_env",
        "lib/vsprintf.c:widen_string",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/block/loop.c:loop_attr_backing_file_show",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:get_bitmap_file",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_output.c:xfrm6_ro_output",
        "net/xfrm/xfrm_output.c:xfrm6_transport_output",
        "net/xfrm/xfrm_output.c:xfrm4_transport_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585133808,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612066002,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:450",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/printk/printk.c:record_print_text",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:eval_replace",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/bpf_trace.c:bpf_d_path",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:bpf_adj_linfo_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_merge_regions",
        "mm/memblock.c:memblock_remove_region",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/namei.c:dx_pack_dirents",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/bitmap.c:bitmap_cut",
        "lib/lz4/lz4_compress.c:LZ4_saveDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:lzma2_lzma",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "lib/kobject_uevent.c:zap_modalias_env",
        "lib/vsprintf.c:widen_string",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/block/loop.c:loop_attr_backing_file_show",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:get_bitmap_file",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_output.c:xfrm6_ro_output",
        "net/xfrm/xfrm_output.c:xfrm6_transport_output",
        "net/xfrm/xfrm_output.c:xfrm4_transport_output",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285216,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614204114,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/fortify-string.h:194",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/printk/printk.c:record_print_text",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:update_event_printk",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/bpf_trace.c:bpf_d_path",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:bpf_adj_linfo_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_merge_regions",
        "mm/memblock.c:memblock_remove_region",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/bitmap.c:bitmap_cut",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:lzma2_lzma",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "lib/kobject_uevent.c:zap_modalias_env",
        "lib/vsprintf.c:widen_string",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168976,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615121901,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/fortify-string.h:194",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/printk/printk.c:record_print_text",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:update_event_printk",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/bpf_trace.c:bpf_d_path",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:bpf_adj_linfo_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "kernel/bpf/verifier.c:adjust_subprog_starts_after_remove",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_merge_regions",
        "mm/memblock.c:memblock_remove_region",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/compat_binfmt_elf.c:fill_files_note",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/audit.c:tomoyo_print_bprm",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/bitmap.c:bitmap_cut",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_lzma2.c:lzma2_lzma",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "lib/kobject_uevent.c:zap_modalias_env",
        "lib/vsprintf.c:widen_string",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622672,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void memmove()
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781696,
      "name": "memmove",
      "external": false,
      "loc": "arch/x86/lib/memmove_64.S",
      "file": "arch/x86/lib/memmove_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781696,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 423
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
void memmove()
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595947760,
      "name": "memmove",
      "external": false,
      "loc": "arch/x86/lib/memmove_64.S",
      "file": "arch/x86/lib/memmove_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595947760,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 423
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
void memmove()
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596944352,
      "name": "memmove",
      "external": true,
      "loc": "arch/x86/lib/memmove_64.S",
      "file": "arch/x86/lib/memmove_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596944352,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void memmove()
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597871824,
      "name": "memmove",
      "external": true,
      "loc": "arch/x86/lib/memmove_64.S",
      "file": "arch/x86/lib/memmove_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597871824,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510801400,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/fdt.c:fdt_move",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_splice_",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": [
        "lib/fdt.c:fdt_move",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_splice_",
        "lib/fdt_sw.c:fdt_finish",
        "lib/fdt_sw.c:fdt_resize",
        "lib/fdt_sw.c:fdt_resize",
        "lib/fdt_sw.c:fdt_resize",
        "lib/fdt_sw.c:fdt_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503798912,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 340
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243246968,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_merge_regions",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_insert_block",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/reed_solomon/reed_solomon.c:decode_rs16",
        "lib/reed_solomon/reed_solomon.c:decode_rs16",
        "lib/reed_solomon/reed_solomon.c:decode_rs8",
        "lib/reed_solomon/reed_solomon.c:decode_rs8",
        "lib/reed_solomon/reed_solomon.c:encode_rs8",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_execSequenceLast7",
        "lib/zstd/decompress.c:ZSTD_execSequenceLast7",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/fdt.c:fdt_move",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_splice_",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236422608,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302362344,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/powerpc/kernel/module_64.c:module_frob_arch_sections",
        "arch/powerpc/xmon/xmon.c:cmds",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_vio.c:hvterm_raw_get_chars",
        "drivers/tty/hvc/hvsi_lib.c:hvsilib_get_chars",
        "drivers/tty/hvc/hvsi_lib.c:hvsi_get_packet",
        "drivers/tty/hvc/hvsi.c:hvsi_interrupt",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/fdt.c:fdt_move",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_splice_",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282899660,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 0
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
void * memmove(void * dest, const void * src, size_t count)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279761694,
      "name": "memmove",
      "external": true,
      "loc": "lib/string.c:848",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:repair_env_string",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/fdt.c:fdt_move",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_packblocks_",
        "lib/fdt_rw.c:fdt_splice_",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761694,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604578159,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589731824,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604569875,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457504,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604655983,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590175200,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
```

```json
{
  "name": "memmove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604655983,
      "name": "memmove",
      "external": true,
      "loc": "include/linux/string.h:383",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:repair_env_string",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:fixup_bad_iret",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/mm/numa.c:numa_remove_memblk_from",
        "kernel/range.c:add_range_with_merge",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/trace_events.c:trace_event_eval_update",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "kernel/bpf/verifier.c:verifier_remove_insns",
        "mm/memblock.c:memblock_insert_region",
        "mm/memblock.c:memblock_remove_region",
        "mm/slub.c:process_slab",
        "fs/proc/vmcore.c:parse_crash_elf32_headers",
        "fs/proc/vmcore.c:parse_crash_elf64_headers",
        "fs/sysfs/file.c:sysfs_kf_read",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/common.c:tomoyo_parse_policy",
        "security/tomoyo/domain.c:tomoyo_assign_namespace",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/network.c:tomoyo_parse_ipaddr_union",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set",
        "block/badblocks.c:badblocks_set",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/zstd/decompress.c:ZSTD_decompressSequences",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run",
        "lib/xz/xz_dec_bcj.c:bcj_flush",
        "drivers/video/fbdev/core/fbmon.c:fb_create_modedb",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/hvc/hvc_console.c:hvc_push",
        "drivers/tty/hvc/hvc_console.c:hvc_console_print",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_attr_do_show_backing_file",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up",
        "drivers/ras/cec.c:cec_add_elem",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_xdp_adjust_head",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_options.c:ip_options_undo",
        "net/ipv4/ip_options.c:__ip_options_compile",
        "net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_restore_cb",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_delopt",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_restore_cb",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/vsprintf.c:widen_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590225648,
      "name": "memmove",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 409
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
void * memmove(void * p, const void * q, __kernel_size_t size)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * q</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>void</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * dest</code>
</li>
<li>
<b>Param added. </b>
<code>const void * src</code>
</li>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * q</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
</ul>
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
