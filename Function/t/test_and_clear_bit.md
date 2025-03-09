# Function: <code>test_and_clear_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578882509,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905837,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907330,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931061,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/rapl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578935046,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977237,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079405,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098806,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126533,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258432,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307998,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579390527,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502425,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579745231,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882974,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889456,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454280,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468407,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519643,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580562306,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602735,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_shepherd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606756,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692026,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713696,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724167,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756633,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884035,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949696,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224919,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406703,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_writeback_dquots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437477,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889367,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915865,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068443,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183361,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184926,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/key.c:key_reject_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790698,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582807500,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583203234,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221662,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224887,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583977023,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583990862,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002444,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584014973,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095589,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584813495,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840599,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585063326,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585169294,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585241867,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585516474,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585595357,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706055,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725664,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_start_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783192,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586173135,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586265385,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_wake_subqueue",
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:napi_complete_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403003,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586453509,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586662946,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883785,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902999,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578932055,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_cpu_dying",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_exit_boxes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977221,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579075345,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098326,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126645,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579257844,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306409,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579403228,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516489,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579767886,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912526,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919022,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529751,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547751,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580569465,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580617552,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580654231,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710212,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580805896,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828700,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878873,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020892,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034187,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104230,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391799,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595543,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085524,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102384,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284377,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399633,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402067,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076229,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086604,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583512954,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583528798,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532563,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584322974,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584345300,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585174564,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203239,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585452686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585571712,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585635622,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585911850,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989421,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586104439,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148768,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586185812,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593838,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586690457,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_wake_subqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845762,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586899605,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587109282,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813247,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:250",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_remove_filter"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883849,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578903191,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578932304,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978933,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579073985,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096475,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119764,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133941,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579271360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321913,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423756,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538638,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793375,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827457,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943061,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949600,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593739,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613940,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684598,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580721442,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776036,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870952,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894301,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913453,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946960,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095492,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179376,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581470215,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686520,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708600,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175620,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192480,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582372773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491825,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494259,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583185237,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194716,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583652762,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664830,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668517,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037762,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:__acpi_ec_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505006,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527140,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584951087,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585369348,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397943,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585656782,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585759408,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823238,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099996,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586177549,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305127,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586351642,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586389894,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586778206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586876425,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_wake_subqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093797,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588026671,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588031648,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_remove_filter"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883022,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925424,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979605,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579065502,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088363,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112285,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133109,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579268064,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320494,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411516,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525558,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791919,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864585,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952197,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957536,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580623967,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580637409,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717983,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756762,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813246,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916016,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939229,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954691,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991627,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142167,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147816,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227694,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525735,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740122,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755105,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262100,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582278340,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457220,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582572691,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575126,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236171,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583250956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583257693,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583692233,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706553,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583708517,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584097155,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584584318,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611021,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584973283,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585035937,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585453923,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482523,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585743518,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585847473,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585909686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586183562,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264826,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403885,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586451944,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491980,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717622,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586899338,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012714,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_tx_wake_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164510,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222341,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588184751,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189767,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:263",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_remove_filter"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884862,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578927536,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982594,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579074466,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099147,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125581,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147497,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579285040,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343779,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440380,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551579,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825430,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863205,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865790,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908137,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997893,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003328,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580704885,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719569,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803502,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844110,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903346,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015388,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039069,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058259,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095624,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264369,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282740,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358689,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668055,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878156,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912146,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411140,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427476,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608004,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725425,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727926,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583417180,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583430352,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437369,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583949071,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583963945,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583965916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584368339,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584996398,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023565,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585177282,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585394227,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458769,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884723,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585913963,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586177683,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586286151,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586350470,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586628895,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586728250,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870061,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586919153,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959793,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587201878,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587391066,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510666,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_tx_wake_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587736986,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588735943,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_remove_filter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886397,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930418,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985317,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079010,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104699,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121319,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134314,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157173,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354877,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455366,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579859190,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579899918,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944280,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049973,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836921,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855089,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940254,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950011,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580981001,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039250,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149831,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175097,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197068,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236348,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431380,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507091,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831482,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582064274,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582093970,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617745,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800990,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923889,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926277,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583372304,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641517,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648857,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583793071,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584141980,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158489,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584160501,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584589619,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585230574,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585257046,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585412831,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585636828,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702309,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586131236,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161224,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431939,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586544681,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608086,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874346,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586994698,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163724,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587212925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587254936,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587502418,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587691914,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814715,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_tx_wake_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073781,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589094990,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:265",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932226,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983669,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579083541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110331,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146661,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579195643,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321040,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382029,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487670,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579906413,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943245,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579947307,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991368,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096789,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102736,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905353,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923553,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016238,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026171,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058025,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116834,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229655,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255417,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280412,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319760,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494744,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503057,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592965,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918730,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157330,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189738,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703060,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719489,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904102,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949644,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032417,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583034805,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747789,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874911,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584229596,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584246313,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584248273,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584687027,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585179072,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585349870,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585376447,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585536527,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585762316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585830565,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134943,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586274244,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586303112,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577667,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586693529,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586756966,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587155930,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343644,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393300,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435672,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682418,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826010,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949515,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:netif_tx_wake_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588250773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589322158,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:264",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887461,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937509,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996949,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579093205,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120283,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158757,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579208530,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336224,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397505,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505974,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579940852,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982018,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985970,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033161,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140693,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146658,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003688,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019441,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080075,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090875,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122538,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181454,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303954,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330217,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355006,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589943404,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430827,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602664,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612732,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705363,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055937,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320211,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353108,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893153,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082415,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583130622,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214241,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217365,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677990,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936988,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065535,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584419324,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437785,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584441874,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887478,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392034,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585470738,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585563038,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590363,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756619,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586001348,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065596,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369347,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586419856,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586517873,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586546248,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_release_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586829334,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586945761,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012473,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587293643,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587421085,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587614541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664812,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708985,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587961570,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588128840,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259739,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588641845,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589780766,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888933,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939989,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998453,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122171,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161253,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579210786,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340432,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400817,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518340,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579532022,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579990772,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032275,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580036098,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083881,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188837,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194706,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057624,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074817,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136059,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147595,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179567,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581239582,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362530,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389626,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414542,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170959,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488046,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581495051,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673352,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683644,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776835,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582133713,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419171,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452004,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582982676,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999729,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583186920,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236867,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583320049,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323173,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583784703,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040460,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188255,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584555676,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574553,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584578610,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023227,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585532690,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585611495,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585704174,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585731179,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585898843,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148518,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213484,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516833,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586566624,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586665985,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975414,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587144497,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587211931,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587494619,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587624141,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818627,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869004,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913289,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588167538,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588333976,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588464859,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864213,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590004462,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893659,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945285,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579107125,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136667,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180981,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579232207,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369852,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410160,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547732,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579563425,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580037893,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_wait_for_interrupt",
        "kernel/irq/manage.c:irq_wait_for_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082134,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086861,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580141657,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260260,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233175,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256528,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581260193,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581320612,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332507,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351266,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581427870,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559793,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586746,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615459,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694019,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701259,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891879,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902028,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000610,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373952,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714801,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748135,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298955,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316545,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511550,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565848,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651921,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655313,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584176047,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435340,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582384,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585228796,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248569,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585253650,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725339,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249586,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586336248,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433182,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462267,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638507,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586906652,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586978840,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298230,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587351300,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587464498,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587760459,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587800854,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587993142,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588064571,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357181,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588488685,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588665635,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588718257,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765085,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033058,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193480,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330843,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589742053,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589870362,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591035275,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591087022,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:mptcp_wait_data"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578889487,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578947040,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007653,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579106933,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134704,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177173,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225327,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368860,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410800,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529428,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579544885,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580021061,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_wait_for_interrupt",
        "kernel/irq/manage.c:irq_wait_for_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064710,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070353,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118889,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237781,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243780,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275748,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298580,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581302513,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581362512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375003,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401498,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471134,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_bdi_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518797,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604399,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632843,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660404,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738884,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748771,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937939,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947480,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049219,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582430256,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785969,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820399,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414251,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431457,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583620560,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583678203,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583773361,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583776778,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584294656,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584551987,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584700047,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585379637,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386909,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585406121,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585410786,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846859,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366896,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454701,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586548238,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577186,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586747307,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586991581,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065400,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359478,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587414421,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587532466,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587819787,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858502,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588052758,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588109867,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387490,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588517965,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692771,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745777,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588785549,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589042530,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589192008,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330907,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589775141,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589910090,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591099243,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163717,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578891934,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951936,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579113477,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141408,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183269,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227727,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373148,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413968,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533684,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579547477,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580022052,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065378,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072714,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122169,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243020,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580248816,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300829,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316132,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581320401,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581381630,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390859,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425549,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491918,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_bdi_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538850,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626859,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654520,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682152,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767178,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776579,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963436,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973652,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075292,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457040,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813553,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849181,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437098,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453697,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643327,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698957,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797489,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583800890,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584328378,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584584803,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604647,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584727779,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585262507,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585271037,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287049,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585291522,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585427440,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725387,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251520,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338400,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433198,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462084,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630443,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872376,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949208,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587240382,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587296413,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587414757,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587699275,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587737482,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587935622,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587992427,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588268820,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401005,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588579139,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588631329,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588671421,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588929874,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589085528,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225787,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589814714,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591029927,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591096991,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:mptcp_flush_join_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591104981,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893203,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962320,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035445,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138725,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168352,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217509,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579266400,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434444,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476848,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606052,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579619541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_clear_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154271,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198821,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206695,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264841,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391679,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580399728,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536505,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561394,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581565828,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581630641,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638267,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672971,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750617,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_bdi_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799145,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894404,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581922670,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951432,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049840,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059442,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246181,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276233,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388081,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780656,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978014,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_hash_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143303,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182237,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583786509,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804289,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584000799,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059581,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584160033,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584163434,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584715884,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999075,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020135,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585155766,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585719515,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727165,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585743833,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585748210,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207010,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586761952,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586858250,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959022,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586989228,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587177067,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587514080,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817030,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863081,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587987077,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290951,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332682,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588545798,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588605515,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588919945,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589067099,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254979,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308753,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349629,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589637586,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803000,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589948011,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590435781,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590578170,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591871271,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591939999,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_flush_join_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591949077,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:81",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578896303,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972992,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056245,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214000,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269237,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318960,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503758,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555024,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698988,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579714005,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_clear_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300097,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351510,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580360968,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580435004,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610183,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618510,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581885931,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913192,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581919460,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581993044,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582003749,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582053353,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132718,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190268,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582296360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329387,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368167,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461566,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582480777,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497134,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714057,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754151,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895449,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332766,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629324,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673194,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584350205,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584369189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585403,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648024,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758913,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762659,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390617,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712197,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585737543,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890934,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586028486,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wqe_hash_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586897526,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901152,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586927161,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586931137,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089708,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587444906,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038800,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588141041,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253998,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286924,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588490316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841664,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165365,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171384,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589213660,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344465,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589675154,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589724314,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589955419,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590018843,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590351462,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590511737,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590723667,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590780457,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590823326,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591016254,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591139074,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591321322,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591483707,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592038293,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592195734,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593586199,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593669223,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593675969,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578908656,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991152,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230549,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269824,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331989,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579385424,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601425,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661840,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824140,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579840789,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_clear_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512129,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580573780,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583960,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677324,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874311,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883790,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318792,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348264,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582355220,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429521,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448117,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508800,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:isolate_folio",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582609806,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677293,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790936,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582829190,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867112,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975486,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994945,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011555,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_cache_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241277,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288209,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441833,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917310,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234338,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280743,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585000189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020725,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585262923,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585329224,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585454401,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458899,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586143299,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586385214,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_unregister_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586492437,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516938,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678575,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864118,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wqe_hash_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588050054,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588053516,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588083033,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588087585,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278428,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588705590,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589417136,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589530833,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589666750,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589703884,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589926988,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590344352,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590717301,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590723832,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590769206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590911985,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591286925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591344154,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591540247,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591620395,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591981972,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592159129,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592398064,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592460317,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592511088,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_unplug",
        "drivers/md/md-bitmap.c:md_bitmap_unplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592726670,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592864306,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593074954,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593267371,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593855589,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:netif_carrier_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594023974,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595512663,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595597802,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595608113,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578906077,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087749,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236357,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276144,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340693,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579395056,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579614177,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676000,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873212,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579890773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_clear_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584593,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656872,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753836,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958196,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967662,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373989,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519970,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551151,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582558321,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634675,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582653215,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582711274,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818590,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887707,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009311,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044443,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583084472,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187342,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219831,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_cache_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583460797,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506919,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657556,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139886,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461720,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510811,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585228125,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247989,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493259,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585559211,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585685745,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690419,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586381738,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_check_last_writer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631582,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_unregister_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586740007,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764186,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586939663,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131030,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_hash_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178575,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324584,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329982,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357369,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588361905,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588554284,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588993798,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589716336,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589831905,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970638,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590008600,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590236348,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489922,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591058485,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591065160,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591110575,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591255297,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591642273,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591705802,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591961916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592042891,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592582585,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592827408,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592885309,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592941568,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593163870,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593301737,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593526458,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593725179,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594230389,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:netif_carrier_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594401574,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596021351,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596107537,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596116849,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578928413,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015296,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097070,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113541,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265381,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305952,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371109,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423440,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710128,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911260,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579929349,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_clear_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648945,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722088,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580838956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049780,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062398,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541317,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688850,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721743,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582729105,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792949,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582824367,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880471,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993070,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060137,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188444,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226281,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266736,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583371189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440068,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455188,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_cache_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583653917,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703927,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853654,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584356062,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684380,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733403,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585461117,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481237,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585729889,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585797627,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932545,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937430,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646328,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_check_last_writer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586902478,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_unregister_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012087,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036666,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220994,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587417654,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_hash_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588469423,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618229,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:gpio_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588624158,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588651865,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588656625,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853948,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589298054,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590053984,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170673,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590309278,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590347112,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_keypress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590577340,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590750613,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_read_and_clear_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590790464,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_read_and_clear_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590840946,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591026064,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591403189,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591409912,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591455903,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591602517,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592381199,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592449418,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592701564,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592782955,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593327321,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593576736,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593634720,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593691359,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593916814,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594058137,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594297882,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594504843,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595027717,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:netif_carrier_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595203209,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596884855,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596987152,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_sk_clone_init",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data",
        "net/mptcp/protocol.c:mptcp_enter_memory_pressure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596991505,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_write_space",
        "net/mptcp/subflow.c:__mptcp_sync_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597106571,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:82",
      "file": "net/handshake/tlshd.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int test_and_clear_bit(unsigned int nr, volatile long unsigned int * p)
```

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490188904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state",
        "arch/arm64/kernel/fpsimd.c:sve_set_vector_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490234896,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490351388,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490448012,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490656324,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490677168,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491178192,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237092,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491416172,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491425376,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492417292,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492448712,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492509452,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492519512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492559664,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492636940,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492767620,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492794896,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492814244,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503919048,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492905412,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492915016,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493130352,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493235708,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493441912,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493678408,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493772212,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__arm64_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__arm64_sys_epoll_pwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493813248,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_pgetevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849500,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494028120,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494066236,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494663904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494687608,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494905212,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494960512,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495060040,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495064660,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495587900,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495874852,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496054684,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496750096,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496808500,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496814640,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497436156,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498192896,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498274880,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498386024,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498432580,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498718848,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498941800,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499020776,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499404000,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499456288,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499566608,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499969580,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499999904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500222772,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500298700,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500634720,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500786316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501033980,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501097740,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": [
        "drivers/md/md.c:md_start_sync"
      ]
    },
    {
      "addr": 18446603336501144876,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501465092,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501759248,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:pmu_free_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501783356,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501798916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501806320,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501830572,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502008228,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502450368,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503748468,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:45",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501066656,
      "name": "test_and_clear_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283355808,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "arch/powerpc/kvm/book3s_hv_rm_xics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_check_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283384696,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283479536,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283500880,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284080736,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284137072,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284210272,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284363656,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284373556,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285682928,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285708360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285798436,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285817540,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285865160,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285953136,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286132376,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286166080,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286195068,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297814016,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286310716,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286321316,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286594440,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286605952,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286754208,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287291032,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287691500,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287727400,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288479696,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288503600,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288769920,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288837524,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288952172,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288957904,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289687860,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290075972,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290288200,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290846248,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290876848,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290884388,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291429956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291570716,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291616128,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291869112,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292079376,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292183472,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292642008,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292717916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292862992,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293296220,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293513932,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293605068,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294053360,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294230800,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294516384,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294594508,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294651808,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294995416,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295229680,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295424908,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296001712,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297584268,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:154",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271346224,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "arch/riscv/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271401916,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271413848,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271729876,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767578,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271892406,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272516558,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272568300,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272577832,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272604392,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272653908,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272744836,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272763824,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272776460,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_referenced_one",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270890242,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272829498,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272837410,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272950336,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024886,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273131820,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273302548,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273370060,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__se_sys_epoll_pwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273401216,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_pgetevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273420126,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273534530,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273556138,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274027188,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274044434,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274216498,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274261334,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274329844,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274332918,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274752712,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274998238,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275130636,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275501388,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275519260,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275522774,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275972718,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276054202,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276082820,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276231330,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276326298,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276388302,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276631964,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276678652,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276762346,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277046120,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277145208,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277206288,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277500206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277608550,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277771924,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277821988,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277857856,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278053686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278174114,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278287856,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278637742,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279665744,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:84",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888933,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939989,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998805,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095573,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122555,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161621,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579209634,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336336,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396721,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492004,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579505686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579959508,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001011,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004834,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052617,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157637,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163506,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026472,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043665,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104907,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116443,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581148415,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208430,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331378,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358474,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383390,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773247,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456894,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463899,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642088,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652380,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745571,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102449,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387907,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420740,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951412,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968465,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583155656,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583205603,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288785,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291909,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583753439,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009196,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156991,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584512604,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529001,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584533058,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584965602,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585294722,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585373143,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465198,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492203,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585659835,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585908886,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973692,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207313,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586257104,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586356465,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586481713,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_scan_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500117,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732422,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586850577,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918011,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200651,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587316957,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587449603,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587499980,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587544265,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587789106,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940760,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071643,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470597,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589608062,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883092,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578936965,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027653,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054507,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093621,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579144610,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326209,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420868,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579434698,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579897348,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939683,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943506,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997929,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580103749,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111122,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972568,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990945,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051995,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063483,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095339,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155182,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275106,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302186,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326206,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496070,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399190,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406075,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583007,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590819,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684195,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039889,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582325603,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359628,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888564,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905617,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092808,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142755,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225921,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229045,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690495,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945020,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584092255,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584450732,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584874411,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585087181,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_nfit_query_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247234,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585335230,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585362043,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585822956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586025681,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586075472,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586101506,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:pmem_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197777,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357841,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_scan_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586368693,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599638,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586792785,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859179,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959403,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587085325,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217811,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268140,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587312361,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587492530,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587653864,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587785067,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588182597,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589332590,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888869,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939925,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998389,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095125,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122107,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161173,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579210706,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336256,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396641,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491924,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579505606,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579951044,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992547,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579996370,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044153,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580149109,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154978,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017672,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034865,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096107,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107643,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139615,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199630,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322578,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349674,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374590,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216655,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448094,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581455099,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633400,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643692,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736883,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092929,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378387,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411220,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940020,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957073,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139688,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583189635,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272817,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275941,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737215,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992956,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140751,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584507340,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584524713,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584528770,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584974811,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585483090,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585561895,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585654574,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585681579,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585849243,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098534,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163500,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586464801,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586514592,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613953,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929974,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587099057,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587166491,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587449179,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587575389,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774771,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825148,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869433,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588122066,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272536,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588403419,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588802773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590050094,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_clear_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888757,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940501,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001077,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579099365,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:enable_cpuid",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127227,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166309,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579215986,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405137,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:pudp_test_and_clear_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524420,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538246,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579997444,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread_check_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039283,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043138,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092812,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_update_patch_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201093,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206994,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078984,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096433,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_check_errors",
        "mm/filemap.c:filemap_check_errors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158315,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169963,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202152,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262910,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386550,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413610,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436686,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590267018,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513231,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519555,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699736,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710076,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805139,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165681,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464049,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:dquot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582490672,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028084,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045553,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233254,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583283475,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367393,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370773,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838143,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:ima_file_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095260,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584244911,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584613612,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632489,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584636546,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_unexport_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080987,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_complete_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590832,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585669863,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585762702,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585789611,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585956859,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207142,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/lightnvm/core.c:nvm_remove_tgt_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586272204,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586576497,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586626336,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726465,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_evt_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587037606,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587206305,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587273563,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:releaseintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556473,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587686957,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888115,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_get_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938796,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:bb_store",
        "drivers/md/md.c:md_super_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587984473,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588239602,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407832,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_wake_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539883,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_hash_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943413,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590100190,
      "name": "test_and_clear_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:183",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int test_and_clear_bit(unsigned int nr, volatile long unsigned int * p)
```
</details>
</li>
</ul>
