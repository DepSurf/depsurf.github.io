# Function: <code>_find_next_zero_bit</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_next_zero_bit(const long unsigned int * addr, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066000,
      "name": "_find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:177",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "io_uring/filetable.c:__io_fixed_fd_install",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066000,
      "name": "_find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long unsigned int _find_next_zero_bit(const long unsigned int * addr, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324256,
      "name": "_find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:195",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "io_uring/filetable.c:__io_fixed_fd_install",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_find_bit",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324256,
      "name": "_find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
long unsigned int _find_next_zero_bit(const long unsigned int * addr, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607200,
      "name": "_find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:195",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "io_uring/filetable.c:__io_fixed_fd_install",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_find_bit",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607200,
      "name": "_find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int _find_next_zero_bit(const long unsigned int * addr, long unsigned int nbits, long unsigned int start)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
