# Function: <code>__roundup_pow_of_two</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595092660,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595100991,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382782,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595127323,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532832,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595147858,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032478,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_proc_fn",
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113733,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707245,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806725,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835156,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_calc_metadata_amount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921173,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:get_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031952,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039781,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068994,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382194,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531613,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272043,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310331,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:intel_alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331166,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584339048,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466217,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585584758,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586091422,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586263223,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586586838,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621861,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586713848,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595260339,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268984,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287055,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368059,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443447,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451363,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595299360,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619360,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595319123,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581191997,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279481,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899536,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582001833,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030180,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_calc_metadata_amount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110997,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:get_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324426,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333523,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363474,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583695760,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583852441,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614470,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584623560,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584656620,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584678062,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584686277,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861764,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978700,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502997,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586688295,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031179,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587066914,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587161587,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:61",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595505364,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595514666,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330671,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580407619,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503930,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512499,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595547374,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580686571,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595567319,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581269150,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357929,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988992,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091287,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449338,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458768,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488562,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833895,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583991801,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584309701,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584796132,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584804824,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584842572,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584864574,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584872837,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586050612,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167020,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874179,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587227292,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587263730,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596425514,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596434493,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342897,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580418755,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533151,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544352,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596472111,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719917,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596494732,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581318145,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413017,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054231,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205540,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469946,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481457,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510898,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875979,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902671,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040025,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584387752,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584885540,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584894232,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584932332,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584954980,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584961826,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134655,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586255643,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998572,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359950,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587396642,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602750332,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602760381,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396337,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474211,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596852,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580622035,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602798929,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580805613,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602821970,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581458181,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:round_pipe_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554633,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205495,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354292,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650890,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662449,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696130,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139451,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584165839,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584303929,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794664,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585329875,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585353772,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585376148,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585383122,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577739,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586719131,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587497260,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880062,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587918354,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602922726,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602934258,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580457889,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536291,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692287,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732367,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580748446,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602972150,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942786,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602995388,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612613,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581710661,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394608,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545132,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583868928,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583878359,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913616,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584356162,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383867,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523517,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585024579,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585569469,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596988,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585626165,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586842348,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586986018,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801645,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223119,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267189,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720871,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732108,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580513361,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595251,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764591,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812670,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772124,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018770,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794510,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698965,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581797173,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493440,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646316,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583954224,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_init",
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961706,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998304,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451223,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584474494,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584620381,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585132643,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695373,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721788,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748352,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585753365,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998700,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147410,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936781,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223486,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588410479,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588455669,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589356933,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:59",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604821669,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604833337,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580571280,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653747,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841932,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901759,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080869,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604891254,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604897455,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816597,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581916005,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191203,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665894,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582819197,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134160,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584141405,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181872,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647964,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584672336,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584818481,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585339227,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585922102,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585948394,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978957,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585985060,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257823,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412450,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588246207,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588560272,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588623848,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588814282,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588861669,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589814005,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604856041,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604867498,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618432,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700358,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892972,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941150,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580954943,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136853,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604925153,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604931397,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889157,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581988389,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272083,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767889,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582922373,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256560,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584263853,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584315664,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584785468,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584810608,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584953521,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477771,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586056674,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586089018,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125728,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586132068,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458191,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615570,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588450367,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588777344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588845976,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037594,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589085253,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590038965,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609186606,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609196533,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717168,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817366,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038287,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100429,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118360,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321333,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609239177,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609245665,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116853,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582221845,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537507,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079121,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238629,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583823423,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_compute_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616724,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584664064,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584670918,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584725600,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477597,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503483,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585648717,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586198494,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782184,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809155,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586833344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586838343,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_alloc_iova",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586878655,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586885254,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:alloc_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297269,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_streams_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588477221,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589318591,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589650859,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589729967,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998394,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590049749,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612252249,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612263114,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706608,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808182,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046747,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128489,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581139951,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150917,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365367,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612305572,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612312024,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170531,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582269349,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607187,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156439,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340437,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944657,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735540,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584781392,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584788534,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839091,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518237,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585635547,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591425990,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586317886,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586868179,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890012,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901102,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586927820,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586939456,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962792,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467204,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355017,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513744,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589317631,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589675409,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590040682,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096277,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614393788,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614404058,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710720,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812710,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061579,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096400,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149236,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581167733,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384880,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614445785,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614452559,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195171,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582294853,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620645,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182615,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363333,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971649,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763524,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584825424,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832324,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584883347,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585336713,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585400403,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515550,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591367428,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191485,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586743907,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586770926,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780184,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810140,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586821008,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586844491,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349124,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588237780,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588397120,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589213295,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589657761,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589954884,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590010501,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615328051,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615339422,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888772,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005334,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286731,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325767,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382616,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406809,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562619,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634229,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615388570,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615395662,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512479,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582613669,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944422,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524578,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706218,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337207,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192179,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585243792,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251324,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309059,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585787068,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_restore_rebar_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585859244,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585984234,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592401662,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586693749,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299219,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326124,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334377,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369242,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587380916,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587406004,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915536,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588884155,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062444,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937919,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590414453,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590722072,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590781552,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __roundup_pow_of_two(long unsigned int n)
```

```json
{
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617111399,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617124410,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123741,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254764,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583114,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616509,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629719,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705686,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730758,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915547,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581999254,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617178489,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617187339,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029493,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583148037,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057831,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260340,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584958263,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481237,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585931720,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594107976,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_uring_create"
      ]
    },
    {
      "addr": 18446744071586085024,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586093323,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166291,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586968137,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_restore_rebar_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587052536,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:msi_setup_msi_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587199876,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594266827,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587965888,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588606659,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588640860,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588648497,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588680349,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588689639,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588733917,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589268711,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590312328,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590499695,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591470786,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592011857,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592351082,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592415984,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107976,
      "name": "__roundup_pow_of_two",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627777152,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697662,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_adjust_nareas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627794953,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433821,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586490,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962436,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000829,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016410,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112150,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138454,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350731,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435566,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627869600,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627882726,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583593733,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583720853,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690439,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909956,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671255,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586243045,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586723016,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586761398,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587067648,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587076779,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160659,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884818,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588132553,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_restore_rebar_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588236072,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:msi_setup_msi_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427412,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588613989,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589327648,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590069247,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590111144,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590121358,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590160518,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168533,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590219117,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590831543,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591937752,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592146255,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593238866,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593825629,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594190362,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594268224,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594367015,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594442075,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_pernet_init"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619540028,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580775902,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_adjust_nareas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619557833,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530652,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708173,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150500,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192742,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208486,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308246,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335692,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553627,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640990,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619619393,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619645948,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810325,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583937877,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915792,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138724,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901015,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586482821,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586986018,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027933,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326224,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335723,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423827,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588156379,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407497,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_restore_rebar_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588511576,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:msi_setup_msi_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588704932,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901989,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589625818,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590387455,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590424888,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590434798,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590475158,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590482790,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590538510,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591173576,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592360264,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592569679,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593699906,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594200173,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594577466,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594654320,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594755303,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594832283,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_pernet_init"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621838924,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580862606,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_adjust_nareas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621859785,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642665,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581824477,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299570,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341638,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357574,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469302,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501948,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724203,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812099,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621923639,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621953064,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016453,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584144213,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585148768,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371508,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149479,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/hashtab.c:hashtab_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586752805,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587267762,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587325869,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587609584,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587619195,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587758611,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588446240,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/stackdepot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588637545,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588702690,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_restore_rebar_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588810168,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:msi_setup_msi_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005780,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589935746,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590729839,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590769050,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590781433,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/iommu.c:__iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590810559,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824875,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590832087,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:alloc_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590895118,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591519576,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592329856,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_split_transfers_maxwords"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593101992,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593314303,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594478978,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594997313,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595381146,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595458384,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595562090,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595644058,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_pernet_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597267992,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/objpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/objpool.c:objpool_init"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510889020,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510903512,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491919292,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492010580,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492218364,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492280276,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492300344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492511140,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510963956,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510971264,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493366052,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493501200,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493837960,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494434092,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494599248,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496135168,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496144268,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496201512,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511081064,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496402664,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its-platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496404424,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its-pci-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496404672,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497052092,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497087992,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497107736,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497774500,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497963056,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/sunxi/clk-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sunxi.c:sun6i_get_ahb1_factors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498845432,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500595536,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500697208,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci-mtk-sch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500765280,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501602388,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501973968,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502343988,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502415384,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502646952,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502701348,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503793344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243377276,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3243390616,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226118192,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226169444,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3226185476,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382960,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 3243450492,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3226954172,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227059184,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 3227345684,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3227869620,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3228041964,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 3229458288,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3229466344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 3229525760,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 3243560812,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3229734076,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its-platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3229735780,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/irqchip/irq-gic-v3-its-pci-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3229783632,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/bus/uniphier-system-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/uniphier-system-bus.c:uniphier_system_bus_add_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 3230265780,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3230292060,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 3230328448,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230596104,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:_div_round_closest",
        "drivers/clk/clk-divider.c:_div_round_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3233056212,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 3233152032,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci-mtk-sch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mtk-sch.c:setup_sch_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3233280560,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3234127460,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3234730300,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3235083604,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235153224,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235351836,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235402464,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 3236412528,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283030664,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup_iov_resources",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_bypass",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283179392,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "arch/powerpc/platforms/pseries/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302522804,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302538968,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285013916,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285148136,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285442844,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285514416,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285536740,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285799304,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302617336,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302625856,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286913016,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287063844,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287469996,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288183732,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288400724,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290392736,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290406376,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290487652,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291089676,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291128688,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294004360,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294216488,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295025380,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295401708,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295871844,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295971976,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296247372,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296313568,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297635840,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270629020,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270641466,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272368386,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272416368,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272430138,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272568984,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270690722,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270696786,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273087050,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273174324,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273417782,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273847240,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273975632,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275194656,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275201720,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275254538,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275700912,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275722918,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275913750,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277466250,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277602010,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278069222,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278274810,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278566704,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278624550,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278788210,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278830460,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279698212,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604761057,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772955,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587232,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580669158,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580861772,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580909950,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580923743,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105701,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604830613,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604836857,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857893,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581957125,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582240819,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736625,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582891109,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225296,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584232589,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584284400,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734220,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584759344,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584904385,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585240299,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585817650,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585850138,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585886096,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585892436,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164223,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587308386,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057151,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588383728,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588452360,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643978,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588691637,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589642565,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604728940,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741870,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533856,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615366,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807900,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580856014,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580869807,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052773,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604799674,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604805918,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795493,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581894693,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178547,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673793,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828261,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584160512,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167789,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219600,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584664988,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690128,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192475,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585676834,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585709178,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585745872,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585752212,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922831,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587076770,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587770239,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588096416,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588165048,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355962,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588403621,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367093,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604838685,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604850142,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580578480,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580660406,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853020,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901198,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580914991,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096901,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604907797,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604914041,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849205,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581948437,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231299,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726481,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880005,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584209056,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216349,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584267312,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735628,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584760768,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584905809,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585428171,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586006690,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586039034,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586075744,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586082084,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412751,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587566818,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588388927,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588715904,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588784536,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080154,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127813,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590084597,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
  "name": "__roundup_pow_of_two",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604860111,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_buf_len_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604871640,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635216,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_array_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717910,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:parse_map_size",
        "kernel/trace/trace_events_hist.c:hist_field_log2",
        "kernel/trace/trace_events_hist.c:hist_field_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580911356,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959916,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580975055,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159109,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:get_init_ra_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604929334,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604935568,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918709,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582018389,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fdtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309555,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811367,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582966773,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584313616,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:__kfifo_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584321341,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rhashtable_init",
        "lib/rhashtable.c:rht_deferred_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373296,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_first_fit_order_align"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584843196,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/pci/msi.c:msi_setup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584868288,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585011185,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585536091,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:clk_divider_bestdiv",
        "drivers/clk/clk-divider.c:_next_div"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114978,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586147130,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586185488,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586190372,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587519199,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676930,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588524671,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588856224,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588925128,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589119786,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167637,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sndbuf_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590134805,
      "name": "__roundup_pow_of_two",
      "external": false,
      "loc": "include/linux/log2.h:55",
      "file": "net/xdp/xsk_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare",
        "net/xdp/xsk_queue.c:xsk_reuseq_prepare"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int __roundup_pow_of_two(long unsigned int n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int __roundup_pow_of_two(long unsigned int n)
```
</details>
</li>
</ul>
