# Function: <code>arch_atomic_add</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578939312,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578944826,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161696,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789750,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917928,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_percpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957442,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791251,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916751,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002991,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581234786,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394969,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437007,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492578,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936005,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172723,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582400486,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463722,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560608,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876482,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585239153,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631525,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587235432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587508441,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587725893,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587741875,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988086,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588121682,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297089,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588356904,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588372100,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588893504,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589015024,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578941232,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946826,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151144,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836340,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974132,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004274,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857619,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992170,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078913,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318083,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476025,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520661,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531527,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021125,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268083,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582499464,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563035,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659540,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986170,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585358305,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780597,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587415877,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587688670,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858213,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875091,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146390,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303938,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588485950,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547333,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562475,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588598326,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589049641,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589116966,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240142,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578947356,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952595,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163572,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870228,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014052,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046992,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950371,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142444,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410576,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429120,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590672,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607537,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642570,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157817,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432547,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582657789,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738228,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834807,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583165198,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036773,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687516,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587967962,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162784,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588182296,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588465686,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588622923,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588702302,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893242,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588958413,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973595,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589009905,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589503268,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589570335,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589692204,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578949789,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955027,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166039,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918836,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064639,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096080,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003283,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200339,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471600,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493344,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654334,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678340,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714640,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235049,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531315,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582759773,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840399,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939957,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271262,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712896,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587237093,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587891769,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588175098,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588368064,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588388090,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588671254,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843790,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588926034,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117322,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182925,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198011,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589234532,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589727323,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589794496,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923515,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578955862,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969903,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180730,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963940,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123190,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157950,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204891,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386824,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497634,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581677639,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699585,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878385,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897757,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933052,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471754,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836825,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583055920,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142672,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239139,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599537,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441992,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588090821,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742972,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589040042,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589232608,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246697,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589536310,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589732573,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589815442,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590094050,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590138368,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590169949,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590209268,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590520497,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590537708,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590746935,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590813523,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952176,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591081733,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578957133,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971599,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176922,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952036,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104822,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142421,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436847,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581247211,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430415,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538146,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581725473,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746547,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921892,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944011,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983613,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008347,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528804,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759261,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909577,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583134336,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224777,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340966,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719928,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586556472,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591585873,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589049370,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231280,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589245961,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545334,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589590566,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761631,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851650,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590140194,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590186672,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590219101,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590259921,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590580401,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590597991,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805914,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590873651,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014754,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591147871,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962187,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976846,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184394,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954740,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107849,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147539,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580440485,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581263923,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450999,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562301,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581746117,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774328,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949652,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969999,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582011447,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037216,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565015,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788179,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936845,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583162006,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252622,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363878,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583744390,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275922,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586441432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591529678,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124736,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589140761,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589443046,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652215,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665247,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589757410,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590054706,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590100656,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590133196,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590173728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590505953,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590523228,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590733013,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590800701,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590947674,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591081327,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578974683,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986232,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218442,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083924,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291525,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605318,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517475,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705384,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826929,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582024321,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056947,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254260,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272646,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313927,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344587,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881879,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115900,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271608,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583499850,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595216,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706791,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106089,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586788613,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586967640,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592641342,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589644525,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843600,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589860585,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177990,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590409267,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590421791,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590516482,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590828404,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875056,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590913116,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590954478,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591195393,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591312843,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591333678,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591545667,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591618810,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591783541,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591919256,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578986426,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001281,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594662440,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219648,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580499882,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580809971,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864633,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934495,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087770,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221442,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451078,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493832,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708811,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719867,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755745,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800286,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839887,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435189,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602204,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775563,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584029418,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134083,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260907,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703215,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588069385,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588263342,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525593,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590849687,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591145612,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591346791,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591383481,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591740258,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592000892,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592020623,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592123586,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592463842,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_coalesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592513696,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592552796,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592594502,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592979367,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593006522,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593235454,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593309512,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593484382,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593643805,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_set_owner_r",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579005882,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024033,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596396888,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596502099,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753787,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095939,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291993,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362031,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582559980,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710922,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962968,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008700,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234523,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242925,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343582,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385375,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584024823,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584206803,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584398670,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662372,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768068,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910539,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587900713,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589450889,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589677128,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592452008,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592540784,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592871708,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593102503,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593146073,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593529570,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593820873,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593836319,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593946306,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594318242,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_coalesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594368384,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594411932,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594458406,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594867575,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594893023,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595136078,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595214388,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595402696,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595574349,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:51",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_set_owner_r",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579005969,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024079,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596927848,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597039587,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835771,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187571,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440601,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493718,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565342,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582766362,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940717,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:folio_add_pin",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179956,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217022,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454584,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463119,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507749,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564653,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606031,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584249495,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436610,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584627214,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584883525,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991412,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139340,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588172285,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589750412,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589981736,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592908514,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592971970,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593310145,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593553993,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593599693,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593995170,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594195597,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594210847,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594322562,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594704816,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_coalesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594757024,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594801324,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594849687,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595259511,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595286026,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595526271,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595610244,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595799548,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596084341,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_set_owner_r",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579030897,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049007,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597853576,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597971555,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580925195,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293763,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549881,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582662166,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597868120,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:__ct_user_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750535,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942830,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115930,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:folio_add_pin",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169893,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363577,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583452520,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583647767,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664477,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705271,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583753309,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583800767,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466135,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584658516,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859374,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585136968,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585223060,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585372124,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586991359,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_driver_tag",
        "block/blk-mq.c:__blk_mq_alloc_driver_tag",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:__blk_mq_alloc_requests",
        "block/blk-mq.c:__blk_mq_alloc_requests",
        "block/blk-mq.c:__blk_mq_alloc_requests_batch",
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436930,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "lib/closure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588463101,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590089151,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590320360,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593656952,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593721921,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594066689,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594326192,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594374285,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594779413,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594992525,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595008211,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595122130,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595509392,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_coalesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595564000,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595612540,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595660535,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596099879,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596123866,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596372943,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596458393,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596650215,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596953221,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:31",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_set_owner_r",
        "net/mptcp/protocol.c:mptcp_try_coalesce"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void arch_atomic_add(int i, atomic_t * v)
```

```json
{
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503949888,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490271288,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490315196,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:cpu_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490414768,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vm_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_fault",
        "virt/kvm/kvm_main.c:kvm_create_vm"
      ],
      "caller_func": [
        "virt/kvm/kvm_main.c:hardware_enable_nolock"
      ]
    },
    {
      "addr": 18446603336490463144,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_get_pud",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490633344,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:get_task_mm",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446603336490656380,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490669248,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490712632,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490790036,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/umh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490798420,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:flush_workqueue_prep_pwqs",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:wq_worker_running"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490857544,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:copy_namespaces"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490864768,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490871744,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/async.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/async.c:async_schedule_node_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490878580,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490881356,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:set_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503925136,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    },
    {
      "addr": 18446603336490992624,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491002344,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491048736,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491056960,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:sched_get_rd",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491086148,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491124952,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491139240,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:freeze_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491166924,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491173516,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491179124,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_forced_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491241416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_expedite_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491247072,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491276060,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491306412,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491442312,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491486668,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491552456,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:online_css",
        "kernel/cgroup/cgroup.c:online_css",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init"
      ]
    },
    {
      "addr": 18446603336491574216,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491590436,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_css_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491619112,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491623884,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:ns_get_owner",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491628668,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491635932,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491702344,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_breakpoint",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491776080,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491828412,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:ring_buffer_record_disable",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_set_head_page",
        "kernel/trace/ring_buffer.c:rb_set_head_page",
        "kernel/trace/ring_buffer.c:rb_set_head_page"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:rb_move_tail"
      ]
    },
    {
      "addr": 18446603336491865612,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491949308,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491958796,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:function_graph_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492077044,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492122416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492288140,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492294128,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492346860,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_refresh"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_fault",
        "kernel/events/core.c:_perf_ioctl"
      ]
    },
    {
      "addr": 18446603336492418088,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492425080,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492430744,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492453332,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492480484,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492503540,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492528648,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492536020,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492556568,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492605684,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_get_inode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492636808,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:set_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492646264,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492720416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753272,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492770184,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492776868,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_link_file",
        "mm/mmap.c:__remove_shared_vm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492797268,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_gather_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492797716,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492821496,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:anon_vma_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492879924,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903676,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492911256,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492915124,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492940928,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492951948,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492958560,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998276,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493020752,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup",
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493027360,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/mmu_notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_notifier.c:__mmu_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493046620,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493097096,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:get_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117632,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493124168,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493159804,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493195044,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493246024,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/zpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zpool.c:zpool_get_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493259856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493286876,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493292964,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493324376,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:alloc_file",
        "fs/file_table.c:__alloc_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493329728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:freeze_super",
        "fs/super.c:alloc_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493352856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:free_bprm",
        "fs/exec.c:would_dump",
        "fs/exec.c:kernel_read_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493366596,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493467488,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:take_dentry_name_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493492748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493505864,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:get_files_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493542800,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mntns_get",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount"
      ],
      "caller_func": [
        "fs/namespace.c:mnt_init"
      ]
    },
    {
      "addr": 18446603336493596680,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493652592,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493678356,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493698664,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493714728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493726232,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493737212,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_prepare_user_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493752036,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493788572,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__arm64_sys_userfaultfd",
        "fs/userfaultfd.c:dup_userfaultfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493804148,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available",
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493838368,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_timeout_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493898400,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493947268,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/binfmt_script.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_script.c:load_script"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493955548,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493969752,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493979688,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494006124,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494011004,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494031740,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494061956,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494074228,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494083420,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:proc_mem_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494135764,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_poll_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494169380,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494174904,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "fs/kernfs/file.c:kernfs_fop_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494185108,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/sysfs/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/mount.c:sysfs_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494202192,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/configfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_make_dirent",
        "fs/configfs/dir.c:configfs_new_dirent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494207092,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/configfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494213684,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494222856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494308136,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494323208,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494351584,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494414036,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context"
      ]
    },
    {
      "addr": 18446603336494452788,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494498184,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494514284,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494613748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494632516,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494664212,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494674016,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 18446603336494683576,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494713952,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494763208,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494779748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_collect_bhs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494864888,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/ecryptfs/miscdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494889884,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_ioctl"
      ]
    },
    {
      "addr": 18446603336494923928,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494949452,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494994864,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495003060,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495055432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495058192,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:copy_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495064492,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/key.c:key_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495083528,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495092188,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495093516,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495097468,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495195104,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_secmark_refcount_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495229380,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495297052,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495315828,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/selinux/xfrm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire",
        "security/selinux/xfrm.c:selinux_xfrm_policy_clone",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495387744,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_open_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495392472,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/condition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/condition.c:tomoyo_get_condition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495400284,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495415868,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_get_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495425312,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511041860,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_init",
        "security/tomoyo/tomoyo.c:tomoyo_task_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495484112,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495499956,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495780152,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495795204,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_set_pm_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495831092,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495859748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_get_driver_tag",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495874688,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496010232,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496111272,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496147944,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496357732,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_prepare_to_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496409608,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496870544,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496976100,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/pci/pcie/portdrv_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497007888,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497020224,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497063528,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/pci/ats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497249940,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283708,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497689676,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497730620,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497756100,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498008848,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498074740,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498196492,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498401868,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room",
        "drivers/tty/tty_buffer.c:tty_buffer_flush",
        "drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498455864,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498710000,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/tty/serial/kgdb_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498712468,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/tty/serial/kgdboc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752180,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498897644,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498926428,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/connector/cn_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/cn_queue.c:cn_queue_add_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498930052,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/connector/cn_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498967428,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498980888,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:really_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499031588,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/devtmpfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499057356,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_forbid",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499080312,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499089728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_system_irq_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499103468,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_add_subdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499210052,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499323880,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499333416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499408400,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499448432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499513604,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499526096,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499556300,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:sdev_disable_disk_events",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499654864,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499968604,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500026244,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500118556,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500154016,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500222684,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500241328,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_start_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500251304,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_anchor_suspend_wakeups",
        "drivers/usb/core/urb.c:usb_block_urb",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500271576,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500308400,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500333816,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500338632,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500343620,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500711180,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500879596,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500882376,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500920292,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-pin.c:cec_pin_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500955324,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501100168,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_seq_next",
        "drivers/md/md.c:md_attr_store",
        "drivers/md/md.c:md_attr_show",
        "drivers/md/md.c:mddev_find",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_handle_request"
      ],
      "caller_func": [
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_seq_start",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:rdev_size_store"
      ]
    },
    {
      "addr": 18446603336501134088,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501165552,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:event_callback",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:dm_blk_open",
        "drivers/md/dm.c:dm_issue_global_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501192416,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501207704,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501210728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy",
        "drivers/md/dm-kcopyd.c:dispatch_job"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501222424,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501248072,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe"
      ],
      "caller_func": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test"
      ]
    },
    {
      "addr": 18446603336501405512,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501408568,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501473784,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501695116,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501763448,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501814560,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "drivers/ras/debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/debugfs.c:trace_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501877876,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501919120,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_morph",
        "net/core/skbuff.c:__copy_skb_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501938364,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__sk_queue_drop_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501960664,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:copy_net_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501998732,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502108072,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502205204,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502249276,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502275240,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502418004,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502444060,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502490636,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_cls_offload_cnt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502507048,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502533028,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r",
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502577024,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:rt_dst_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502617096,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502655432,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502661084,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502694308,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502715672,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502791456,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446603336502820744,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502839412,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502867336,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502958408,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502961816,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502998568,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503004616,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503058428,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503082576,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503124140,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503214236,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503231664,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503267596,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503350380,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503424672,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503438284,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503495796,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446603336503525580,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503548512,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503561344,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503600480,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503637140,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:packet_mm_open",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503690848,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503699036,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503700796,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:28",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490382512,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336490620704,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336490894176,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336491532328,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336491825640,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336492339424,
      "name": "arch_atomic_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336493517184,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336494408672,
      "name": "arch_atomic_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494668240,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336494880896,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336501064696,
      "name": "arch_atomic_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336501249052,
      "name": "arch_atomic_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336502785424,
      "name": "arch_atomic_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336503488864,
      "name": "arch_atomic_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578949789,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955027,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166391,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890948,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033375,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065280,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972083,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169187,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440448,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462192,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623070,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647076,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683376,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203785,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582500051,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582728509,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809135,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908693,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239998,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473920,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586943173,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587522745,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974848,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587994874,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588277990,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588450174,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588532418,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588723706,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789309,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804395,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588840916,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589331691,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589398864,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527883,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578946669,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952627,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097991,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825908,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579977748,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010128,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917827,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115571,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382832,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581404384,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564366,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588564,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622003,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137866,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437283,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582665677,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582746287,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845845,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177150,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343936,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884341,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290905,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687952,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587707978,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587990806,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162862,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588244418,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435690,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588501245,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588516331,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588552852,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589056683,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589123856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253947,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578949725,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954963,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165959,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879108,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024911,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056352,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963331,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160387,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431648,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453392,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614382,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638388,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674688,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582194265,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582490531,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582718365,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798015,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897294,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224030,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585663296,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587191653,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587847913,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588129626,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306624,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326650,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588609814,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588782350,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864594,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159882,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225485,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240571,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589277092,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589768555,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589835728,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589969147,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "arch_atomic_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578950301,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955539,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171143,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579924724,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074798,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107156,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994051,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226195,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496144,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517856,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677726,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704564,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741309,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582271609,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:put_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571123,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582803153,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884880,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984364,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321982,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585771408,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298725,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587962337,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247162,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588441840,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588462074,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588747494,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__sk_attach_prog",
        "net/core/filter.c:sk_filter_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922942,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589006066,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589199850,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265613,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589281067,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589319348,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589819259,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589886992,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590012099,
      "name": "arch_atomic_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:53",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
void arch_atomic_add(int i, atomic_t * v)
```
</details>
</li>
</ul>
