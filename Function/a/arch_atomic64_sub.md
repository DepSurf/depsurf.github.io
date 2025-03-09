# Function: <code>arch_atomic64_sub</code>

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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580637872,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580809056,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116851,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201269,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256209,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293437,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326549,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_one_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357173,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426299,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449110,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459486,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522146,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394225,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913108,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612450,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587714672,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587735197,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188345,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588515779,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877088,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120813,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580682865,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702066,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875680,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898193,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195624,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284995,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339451,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376461,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410827,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_one_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421748,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442464,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab",
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511507,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531864,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543182,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592973,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608018,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782436,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inc_nlink",
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987151,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493057,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828695,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997676,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586762034,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848024,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869309,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373184,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588711299,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588865765,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879909,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/unix/garbage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/garbage.c:dec_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100126,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354445,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751281,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765728,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971944,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262920,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359281,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374212,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449866,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487360,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523259,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555477,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620982,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642946,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652138,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719245,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192457,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665386,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019238,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181030,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587021113,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588152424,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174589,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588775132,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589130288,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589811485,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580801841,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580816688,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026072,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321656,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418959,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435431,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514090,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551776,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620469,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691830,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715035,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724666,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792701,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273558,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767382,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584122806,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584153016,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584314726,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220902,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357672,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588379725,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998732,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354448,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590036317,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580919508,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580943611,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206450,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516456,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620392,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646704,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722714,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762197,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836725,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909400,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929971,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942492,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016420,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538241,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078606,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520912,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726687,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588069201,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223132,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254701,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957263,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590335200,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591068895,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580915636,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248842,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561372,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666562,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693072,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770810,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810277,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888117,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954602,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976826,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989836,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582064900,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608379,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_unaccount_mem",
        "fs/io_uring.c:io_unaccount_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583160924,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629632,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839879,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588114940,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589221804,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253869,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998079,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590387776,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133765,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580919383,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266218,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585495,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688660,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715808,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798247,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838706,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918821,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980352,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004837,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017676,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088868,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584083,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_unmap",
        "fs/io_uring.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187405,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584657795,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584884532,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587996345,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115580,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589156218,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589913060,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590304080,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591064583,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581121895,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507162,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581852834,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960188,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988058,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082648,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129552,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214309,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282485,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307279,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320348,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399489,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900787,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_unmap",
        "fs/io_uring.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530539,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071491,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310341,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588610401,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589834060,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589876278,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590679508,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591091472,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591907691,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581391073,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853623,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246256,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378454,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410194,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521350,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576362,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679541,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582766502,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792539,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812620,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582910467,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584064334,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585796705,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954943,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_buffer_unmap",
        "io_uring/io_uring.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167461,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591357535,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591408218,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592307319,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592742319,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593628055,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581740289,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280049,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733788,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881947,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917090,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039376,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095251,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209062,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_do_shrink",
        "mm/slub.c:free_to_partial_list",
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300926,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331130,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583355074,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441923,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__free_raw_hwp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583464667,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697214,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578548,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586840767,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap",
        "io_uring/rsrc.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861198,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "io_uring/notif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_notif_complete_tw_ext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587161909,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590473938,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memblk_nr_poison_sub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593172842,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594143853,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594613551,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595558269,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580774020,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581899761,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481015,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952599,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097121,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133734,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vfree",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247935,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305095,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427053,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_do_shrink",
        "mm/slub.c:free_to_partial_list",
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583520102,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549969,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583574402,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657677,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__folio_free_raw_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681860,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922459,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586836612,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587107263,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap",
        "io_uring/rsrc.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587127390,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "io_uring/notif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_notif_complete_tw_ext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425068,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796866,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memblk_nr_poison_sub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593626890,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594530910,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595005503,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596066603,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580866693,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_release_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024001,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_charge_modmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649687,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134871,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279226,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300649,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420610,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_do_shrink",
        "mm/slub.c:free_to_partial_list",
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482463,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542967,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715166,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747366,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767810,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853775,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__folio_free_raw_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583876372,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585142544,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587113812,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587388127,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap",
        "io_uring/rsrc.c:io_buffer_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587406462,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "io_uring/notif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_notif_complete_tw_ext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587759852,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140546,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memblk_nr_poison_sub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594402202,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333646,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595818175,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596934441,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:30",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
void arch_atomic64_sub(long int i, atomic64_t * v)
```

```json
{
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491845772,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492116456,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492141448,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492377964,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ]
    },
    {
      "addr": 18446603336492406716,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492733836,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818040,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492838668,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492936520,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492988908,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493026176,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493035324,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493066112,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab",
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493137168,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493161644,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493173780,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493235768,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    },
    {
      "addr": 18446603336493257324,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493485364,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inc_nlink",
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493761340,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493838716,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494433968,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495901652,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_dec_in_flight",
        "block/genhd.c:part_dec_in_flight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495977064,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496012552,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496203244,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500305920,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ]
    },
    {
      "addr": 18446603336501776416,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501873808,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501901364,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502606336,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502995392,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503201156,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503215964,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/unix/garbage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/garbage.c:dec_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503790480,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:69",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492339392,
      "name": "arch_atomic64_sub",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336493228784,
      "name": "arch_atomic64_sub.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336500298424,
      "name": "arch_atomic64_sub.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580770641,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785488,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994920,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290504,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387807,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581404279,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482826,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520512,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589205,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660566,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683771,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693402,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761437,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242294,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736118,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584091542,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584121752,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283462,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926982,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964456,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587986509,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588605116,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588960624,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589639917,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580716817,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731664,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941112,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240405,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330540,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346791,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425114,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462639,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530709,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600647,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622377,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632426,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700061,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582180022,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673286,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584027302,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057416,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218662,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586868150,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587677560,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587699613,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588317100,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672560,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589364445,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580761889,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776736,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986120,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281704,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379007,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395479,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474138,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511824,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580517,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651878,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675083,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684714,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752749,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232774,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725974,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075302,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105512,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584266374,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587175462,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588296232,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588318285,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589041292,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589397008,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590081949,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
  "name": "arch_atomic64_sub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580820033,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835008,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047025,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345544,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442873,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459501,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538918,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576880,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645813,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:discard_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718311,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741702,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751594,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581824509,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311030,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811160,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584177878,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_scale_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584209368,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_waitq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372254,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_alloc_algo_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282534,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588431368,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453629,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:mm_unaccount_pinned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080444,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589440096,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590132157,
      "name": "arch_atomic64_sub",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:58",
      "file": "net/xdp/xdp_umem.c",
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
void arch_atomic64_sub(long int i, atomic64_t * v)
```
</details>
</li>
</ul>
