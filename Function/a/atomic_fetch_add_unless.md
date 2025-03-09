# Function: <code>atomic_fetch_add_unless</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578872435,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087154,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:get_wchan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112703,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625573,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579648277,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579721580,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827653,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579852385,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876599,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919567,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117637,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:exit_pi_state_list",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132944,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580350069,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699404,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871882,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:ring_buffer_get",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_lock_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889823,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_aux_output_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900086,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930051,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_entries_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029807,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053363,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178985,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287956,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338436,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387857,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416249,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589469030,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487244,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521250,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550386,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585800,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622015,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670070,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582011467,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183369,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582207091,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224541,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582241772,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262195,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/kernfs/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/mount.c:kernfs_pin_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270224,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309207,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388837,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507639,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582644945,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105024,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "lib/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/syscall.c:collect_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147797,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584314542,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585073109,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585444885,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585461215,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585534027,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585746031,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585789319,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585859686,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586241000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586537594,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586543391,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586698593,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586731551,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785646,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095703,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587242450,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244350,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587569229,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663610,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587671317,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475409,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587736115,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587844912,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872750,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974330,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035627,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588118270,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588230452,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339855,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360392,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378846,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384824,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401709,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588542041,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550209,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588565457,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588586948,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612504,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588621438,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588741463,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588819027,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850082,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852130,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907639,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915419,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588994978,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101168,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589136270,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589151042,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589176138,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197196,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589361264,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic.h:573",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578872972,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650149,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579858965,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579886583,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911111,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957850,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580150728,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180277,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403829,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580769579,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953836,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997757,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012165,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581029508,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093839,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118019,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249259,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362411,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447977,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499521,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531130,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582627,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595387,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581630193,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665763,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698041,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734487,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740669,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787882,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149998,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190828,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345803,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582372970,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406403,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582434608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341831,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509438,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585277861,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585661973,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585677528,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755572,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977885,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586020671,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586096269,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586484798,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783654,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791127,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586913963,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586956422,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586988955,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044012,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360551,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510814,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587511992,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587845017,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587945803,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587949604,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589934525,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588022921,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588158496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178086,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288064,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588361534,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437118,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567531,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588740084,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588763319,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781920,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786229,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588803576,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952535,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588961346,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588976553,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998345,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589024378,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589033162,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589173770,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589252290,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287495,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291731,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349604,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589417219,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589554533,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589592429,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589605352,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589629760,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589650739,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818336,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873114,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472853,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579687189,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579907653,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579936760,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961214,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007706,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580228293,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452597,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812969,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006796,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052589,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068549,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581083663,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150623,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175059,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307867,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422091,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512201,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564033,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596042,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646722,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665947,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701093,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738051,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771481,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808007,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814036,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860250,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227198,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582271213,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445699,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469802,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505363,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533344,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655218,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757813,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584476519,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645470,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415813,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585802949,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585818504,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585897828,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124893,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586168074,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586243821,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632590,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930039,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586937351,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587038874,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_add_container_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111419,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587155110,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188027,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244412,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587562471,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587713951,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587715112,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588049841,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588151803,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588155600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590161781,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588230379,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588363744,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588383214,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493678,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567966,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643534,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588784651,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588963699,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588987091,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005504,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009829,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589026104,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177049,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589186050,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201001,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589222886,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248936,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589257674,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589398634,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477586,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511927,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516115,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589573845,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589641438,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589778565,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589816797,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589829448,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589854000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589875076,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590044608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581247733,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591178869,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289621,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591674274,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581307461,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591618114,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/asm-generic/atomic-instrumented.h:776",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581552389,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:561",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592791298,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:561",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581903573,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:596",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594690882,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:596",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582337589,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:596",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596427671,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:596",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582539205,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:1484",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596968455,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:1484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580228434,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:1484",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_tick_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708357,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:1484",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_try_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597896743,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic/atomic-instrumented.h:1484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int atomic_fetch_add_unless(atomic_t * v, int a, int u)
```

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490863536,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491108432,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491204896,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491476916,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:__arm64_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491729792,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492139604,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492349896,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_mmap"
      ]
    },
    {
      "addr": 18446603336492410116,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492429600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492449292,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492526968,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492555148,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492716424,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492822532,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492934620,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998612,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493035584,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493108640,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493144868,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186924,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493229264,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493273364,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493281508,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493330252,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493795588,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493851404,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494065128,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494089552,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494131768,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494167208,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494221856,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494300588,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494437240,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494600240,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496478664,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496891192,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497730880,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498519128,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498537108,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498615788,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498621812,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498716648,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498963976,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499060944,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499526208,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499893740,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499911348,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499921508,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500012992,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500183412,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500233048,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500271404,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500343100,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500711216,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500879860,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500880988,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500890196,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501320688,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501404676,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501408276,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501434176,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503915412,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501684684,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501762968,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501870968,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501905304,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502024900,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502113808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502219000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502354252,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502566388,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502591372,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502611684,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502616928,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502634592,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502786852,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502802796,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502821088,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502862604,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502876808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502885688,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503047316,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503136084,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503177428,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503181436,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503248348,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503333368,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503488940,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503524480,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503541292,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503570824,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503594516,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503805704,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492337528,
      "name": "atomic_fetch_add_unless",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224702000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:get_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3224883008,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225112396,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225145132,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 3225173128,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3225223548,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3225455328,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:__se_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3225481884,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533396,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545960,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551604,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225556264,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573624,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 3225679496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 3226032244,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 3226234856,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3226293880,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226324068,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226373596,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 3226394332,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226417808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226482348,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226629240,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226722232,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 3226752136,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226769720,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226805408,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226847076,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226879632,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226885260,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3226924868,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3227060460,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__fget"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 3227306392,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3227315632,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 3227350376,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3227518228,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3227532216,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 3227580668,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3227607132,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 3227652564,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227746040,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227882624,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3228042648,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 3229123476,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229161044,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229200264,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3229222412,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229323860,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3229783072,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/bus/ti-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229791620,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230169192,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3230555840,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231174260,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3231188936,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3231243608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3231343808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3231467616,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3231534216,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3231616060,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 3231993016,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232444448,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 3232464752,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup"
      ],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ]
    },
    {
      "addr": 3232466052,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3232535688,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232564404,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/net/ethernet/ti/davinci_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232580460,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232608028,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/net/ethernet/ti/cpsw_ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3232662664,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232709428,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3232743204,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232802196,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233166240,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233179832,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233216804,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/usb/musb/musb_gadget.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233388584,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233389628,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233399716,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233453052,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/power/avs/smartreflex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/avs/smartreflex.c:omap_sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233807172,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3233829960,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled"
      ],
      "caller_func": []
    },
    {
      "addr": 3233893900,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233897800,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233924420,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3233963132,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_set_power_noreg",
        "drivers/mmc/host/sdhci.c:sdhci_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3233997768,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3236533000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 3234101276,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/clocksource/timer-ti-dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234211420,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3234313508,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3234638672,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234661712,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 3234776744,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3234846528,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 3234941316,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3235091484,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4",
        "net/core/dst_cache.c:dst_cache_per_cpu_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3235272696,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235297392,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235317904,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235322708,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235341168,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235496540,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 3235506736,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235522812,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3235549468,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235571920,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235580372,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235731852,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 3235816096,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3235851936,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235856864,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3235920376,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235992960,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3236142564,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3236178404,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236191204,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 3236218096,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236239764,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 3236428764,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/arm/include/asm/atomic.h:130",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232458984,
      "name": "atomic_fetch_add_unless.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282305716,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:show_stack",
        "arch/powerpc/kernel/process.c:get_wchan"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282495464,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/iommu.c:iommu_tce_table_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282595612,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282937644,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283378472,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "arch/powerpc/perf/core-book3s.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283729496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283846384,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284000280,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284108496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284388436,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284431464,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:__se_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284748608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285341232,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285509584,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_get_fd_by_id"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285630580,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:ring_buffer_get",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_lock_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285657748,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_aux_output_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285697000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285722580,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285821456,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285858840,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286061104,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286369296,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286425564,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286469708,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286546900,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286583336,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286633132,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286673200,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286742620,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286800392,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286871456,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287345208,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_prepare_user_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287514956,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287625840,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287778740,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287819412,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/proc/proc_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_open_net"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287904752,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_get_unless_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287918700,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288030476,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288198872,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288402288,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288848168,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_file_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288875592,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_rcu_getref"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288961328,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288972300,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289490124,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289510780,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289547668,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289558608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_find_child"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289575500,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289581004,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289604332,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289612652,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289625692,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/label.c:__label_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289643808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289651468,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289660332,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290049424,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290187416,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "block/bsg-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290626228,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "lib/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290686776,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290978684,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291695860,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_install"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291735940,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_get_by_index"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291761112,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291865336,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291933908,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:set_current_rng"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292109656,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292236672,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292769376,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292780544,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292785152,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292797216,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292817664,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292868288,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293219352,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293463776,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293519796,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293567384,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293651764,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294142088,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294341852,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294344184,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294854960,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294964720,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294974360,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295116592,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295279092,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295323208,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295382328,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295544304,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295711136,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295792148,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295870004,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295969688,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296034868,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_refcnt_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296168836,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296187896,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296249636,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_established"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296259436,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296317452,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:inet_reqsk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296525012,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp4_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296649592,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_create_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296689684,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296721424,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296790872,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296799284,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296849216,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296892732,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297003924,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297122612,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297192204,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:udp6_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297216780,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297392268,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_doi_getdef"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297429044,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297645072,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave",
        "lib/dec_and_lock.c:_atomic_dec_and_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297673268,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297678940,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/powerpc/include/asm/atomic.h:213",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
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
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271521616,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271540660,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271689022,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271745886,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271898392,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271920728,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:__se_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272299910,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_map_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272412736,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_get_fd_by_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272480894,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_set_output",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_lock_task_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272502000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_aux_output_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272520042,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272580780,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272600680,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272779924,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853004,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272870470,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272900390,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272906714,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272955232,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272960314,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273025376,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273028152,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273061698,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273344692,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_prepare_user_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273381316,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273415390,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273442840,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273502694,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273558236,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273578638,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273593234,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273612112,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273620142,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/proc/proc_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_open_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273636118,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273669074,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/configfs/item.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_get_unless_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273678014,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273751432,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273857448,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273976466,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274269656,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_file_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274288730,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_rcu_getref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274335776,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274341912,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274635702,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274647624,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_get_task_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274671042,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274677498,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_find_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274688050,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274698682,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/lsm.c:apparmor_cred_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274702588,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/resource.c:aa_task_setrlimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274707750,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274715098,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "security/apparmor/label.c:__label_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274726022,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274730650,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274736418,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274980654,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275069790,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "block/bsg-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275367258,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "lib/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275406830,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275584506,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276131856,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276147504,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_get_by_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276156694,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276228836,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276266754,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276344542,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276417208,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276703762,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276710302,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276714720,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276720106,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276732442,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276769342,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276993726,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277007600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277110770,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277149754,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277181472,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277232548,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277559682,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277670398,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277672212,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278007638,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278013810,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278038094,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278121026,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278186532,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278223038,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278260854,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278314690,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278370490,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278458894,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278520682,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278565650,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278571950,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278625036,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278657394,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_refcnt_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278724912,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278745616,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278749714,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278761630,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278765344,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278780264,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278789104,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278796536,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278832546,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:inet_reqsk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278913146,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278920364,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278935060,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278971196,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp4_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278979230,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278985662,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279048470,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_create_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279074070,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279094704,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279111608,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279137320,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279144076,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279182084,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279210058,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:__xfrm_state_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279218442,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279222992,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279277212,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279285556,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279362714,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279404858,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:udp6_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279423180,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279458364,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279493066,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279505340,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279527946,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279536640,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update",
        "net/ipv6/calipso.c:calipso_doi_getdef"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279548192,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279566060,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279702444,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279720812,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279723930,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "arch/riscv/include/asm/atomic.h:202",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873114,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663509,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579879765,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579904600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929934,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976442,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197093,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421397,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781769,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975596,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021437,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581037397,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581052511,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119471,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143907,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276715,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390939,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480937,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532769,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564778,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615458,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634683,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669829,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706787,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740217,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776743,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782772,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828986,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195934,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239949,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414435,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438538,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582474099,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582502080,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623954,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726549,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445271,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595950,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585563941,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658820,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885261,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585928442,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586004029,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323070,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586687063,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694367,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586817499,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586861190,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894107,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950492,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587258807,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587674833,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587773371,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587777168,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589764069,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587842075,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587970528,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587989998,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100462,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174702,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588250270,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588391035,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588570083,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588593475,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588611888,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616213,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632488,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783433,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792434,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588807385,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588829270,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855256,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588863850,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589003898,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081954,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116295,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120483,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589178213,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589245806,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589382933,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589421165,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589433816,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589458368,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589479444,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589646864,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866746,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579591861,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579630084,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_tick_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814757,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579843784,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868222,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914250,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580144533,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368469,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727945,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922660,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967533,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983477,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580999775,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066463,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090851,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223124,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333643,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423265,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474545,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506346,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556786,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575665,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609365,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645775,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678857,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714919,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720932,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766650,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582133406,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177693,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352131,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582375706,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411331,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439312,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582561122,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663717,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584380951,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525758,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433765,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585445000,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585745037,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777578,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853149,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164398,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586555399,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562703,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586686794,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_add_container_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759339,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586802582,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586835227,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891644,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929950,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027255,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587448705,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486773,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587548405,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587683632,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587703102,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813374,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887534,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587963086,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588103723,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588282067,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305459,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588323872,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328197,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344472,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588495369,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504370,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588519321,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588541206,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567192,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588575786,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588726954,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806994,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841335,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588845523,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588903205,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588970798,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589107925,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589146157,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158808,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183360,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204436,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589372736,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873050,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660773,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579867925,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579897032,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579921486,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967978,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188565,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580412645,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773017,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966844,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012637,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028597,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581043711,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110671,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135107,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267915,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382139,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472249,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524081,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556090,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606770,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625995,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661141,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698099,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731529,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768055,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774084,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820298,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186414,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230429,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404915,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429018,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464579,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492560,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613810,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716405,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428183,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595630,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366213,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585753349,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585768904,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585848228,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074909,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118090,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193837,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580558,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884599,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891911,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586993434,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_add_container_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065979,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587109670,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587142587,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198972,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587517031,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670095,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587671256,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588005985,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588106331,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588110128,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590207477,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184859,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588302304,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321774,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588432238,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588506526,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582094,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588723211,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588902259,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930769,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:gc_worker",
        "net/netfilter/nf_conntrack_core.c:early_drop",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943790,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_conntrack_standalone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588949542,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_conntrack_expect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589006357,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_conntrack_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589029651,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048064,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589052389,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589068664,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219609,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228610,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589243561,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265446,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589300234,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589440282,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518818,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553159,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589557347,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589615077,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589682670,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589819797,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589858029,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589870680,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589895232,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589916308,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590090240,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "atomic_fetch_add_unless",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873402,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_add_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478181,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579694880,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579913349,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579943064,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967502,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014602,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240814,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468229,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831241,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027955,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073901,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089989,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581105396,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172975,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197587,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331771,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446009,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537078,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589011,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621130,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673170,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692349,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727509,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765235,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799817,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836919,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843044,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888712,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262574,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307064,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582484499,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582500346,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582543829,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582573194,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696676,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801205,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534311,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703326,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473525,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585861301,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585878472,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585955844,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586183147,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586226698,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302413,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692782,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990961,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998295,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587100602,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_add_container_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587173147,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587217174,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587250411,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306044,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624935,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776479,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587777640,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588121425,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223867,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588227664,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257845,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588302723,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437679,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588457198,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588568586,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643668,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588719582,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588863625,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044819,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589068613,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087245,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091573,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589108049,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589257337,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589268752,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589284224,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308589,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589332984,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589342072,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589484922,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589565890,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589600600,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589604851,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589663413,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589731866,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871073,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589909421,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922168,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589947552,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968920,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590140496,
      "name": "atomic_fetch_add_unless",
      "external": false,
      "loc": "include/linux/atomic-fallback.h:1084",
      "file": "lib/dec_and_lock.c",
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int atomic_fetch_add_unless(atomic_t * v, int a, int u)
```
</details>
</li>
</ul>
