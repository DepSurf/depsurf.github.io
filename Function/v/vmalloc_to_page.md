# Function: <code>vmalloc_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730752,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:234",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vwrite",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:add_swap_count_continuation",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/md/dm-io.c:vm_get_page",
        "net/netlink/af_netlink.c:netlink_mmap",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730752,
      "name": "vmalloc_to_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849632,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:235",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849632,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920112,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:235",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920112,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964576,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:268",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964576,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071024,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:266",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071024,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208112,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:266",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208112,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289280,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:266",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289280,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363952,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363952,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423600,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423600,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626800,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:350",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_chunk_addr_search",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:bio_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626800,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672496,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:349",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_chunk_addr_search",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:bio_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672496,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698816,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:617",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698816,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:645",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592201912,
      "name": "vmalloc_to_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581970592,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:646",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978723,
      "name": "vmalloc_to_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582393760,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:665",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596034673,
      "name": "vmalloc_to_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582900016,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 887
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:659",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:aligned_vread_iter",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596556662,
      "name": "vmalloc_to_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583115152,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:659",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/dma/ops_helpers.c:dma_common_vaddr_to_page",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:aligned_vread_iter",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/blk-map.c:blk_rq_map_kern",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597460906,
      "name": "vmalloc_to_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583298048,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492825800,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/insn.c:__aarch64_insn_write",
        "virt/kvm/arm/mmu.c:create_hyp_mappings",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable",
        "drivers/iommu/dma-iommu.c:__iommu_dma_free",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492825800,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226631392,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/patch.c:__patch_text_real",
        "kernel/relay.c:relay_buf_fault",
        "kernel/events/ring_buffer.c:perf_mmap_to_page",
        "kernel/events/ring_buffer.c:rb_free_work",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "sound/core/pcm_memory.c:snd_pcm_lib_get_vmalloc_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226631392,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286208976,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-flash.c:image_data_write",
        "arch/powerpc/platforms/powernv/opal-flash.c:image_data_write",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286208976,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272781770,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272781770,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392448,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392448,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335152,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/hv/channel.c:virt_to_hvpfn",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335152,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383648,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383648,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct page * vmalloc_to_page(const void * vmalloc_addr)
```

```json
{
  "name": "vmalloc_to_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447664,
      "name": "vmalloc_to_page",
      "external": true,
      "loc": "mm/vmalloc.c:269",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/relay.c:relay_buf_fault",
        "mm/percpu.c:per_cpu_ptr_to_phys",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/vmalloc.c:remap_vmalloc_range_partial",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_pfn",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swp_swapcount",
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault",
        "block/bio.c:bio_map_kern",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/md/dm-io.c:vm_get_page",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa",
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447664,
      "name": "vmalloc_to_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
