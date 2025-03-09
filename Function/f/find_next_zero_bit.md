# Function: <code>find_next_zero_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031280,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:70",
      "file": "lib/find_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/pid.c:alloc_pid",
        "mm/percpu.c:pcpu_next_unpop",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/idr.c:idr_get_empty_slot",
        "lib/idr.c:ida_get_new_above",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031280,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583323728,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:70",
      "file": "lib/find_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/pid.c:alloc_pid",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_get_empty_slot",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323728,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448640,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:70",
      "file": "lib/find_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/pid.c:alloc_pid",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_get_empty_slot",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_get",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448640,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469264,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:70",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/pid.c:alloc_pid",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_add_filter",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469264,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650208,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:70",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_add_filter",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650208,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868288,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:80",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868288,
      "name": "find_next_zero_bit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953568,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:80",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953568,
      "name": "find_next_zero_bit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133376,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133376,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255776,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255776,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663472,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:84",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:choose_devnum",
        "drivers/usb/core/hub.c:choose_devnum",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663472,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780832,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:86",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
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
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_test_and_clear_bits",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:choose_devnum",
        "drivers/usb/core/hub.c:choose_devnum",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780832,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614257078,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ]
    },
    {
      "addr": 18446744071579239288,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250563,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562374,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511340,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297258,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978179,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583057519,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583196276,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_test_and_clear_bits",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779538,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585058207,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078482,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247670,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514866,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298046,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931057,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780801,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591034900,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591134696,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188373,
      "name": "find_next_zero_bit.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615177970,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ]
    },
    {
      "addr": 18446744071579276589,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291138,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638043,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769820,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616202,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313988,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395359,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539491,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_test_and_clear_bits",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585210290,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585504447,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525305,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703620,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983410,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587864654,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588541135,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590540225,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591877012,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591986072,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:81",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592051546,
      "name": "find_next_zero_bit.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616943852,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ]
    },
    {
      "addr": 18446744071579330298,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345661,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734258,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150971,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150793,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821442,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583910143,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072689,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585374828,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586004842,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_fixed_fd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586046739,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586653205,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678555,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732137,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586871487,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198817,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588050051,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589211026,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951063,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592149822,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593718996,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593743240,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:89",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818190,
      "name": "find_next_zero_bit.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627552272,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394757,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415563,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860826,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632906,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724390,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584443747,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535999,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705358,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125818,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791949,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:__io_fixed_fd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030219,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587900581,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588019839,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426593,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429187,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590766454,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591535359,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593976042,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654124,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595679772,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595758795,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595895094,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:138",
      "file": "lib/vsprintf.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619301584,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406069,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579427678,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910942,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842023,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116718,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583941446,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673588,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584765103,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584929134,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586364439,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057408,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:__io_fixed_fd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587285371,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174990,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_find_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588294239,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588704514,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728339,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591107878,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591957286,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593346762,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/firmware/efi/unaccepted_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594353162,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596162924,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596189960,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596283131,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412572,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/vsprintf.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621595152,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434357,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579457262,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950190,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017110,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_find_block_fit",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583299614,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147046,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:alloc_fd",
        "fs/file.c:alloc_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584906308,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584998175,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_inode_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160686,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630874,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:scope_to_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335504,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:__io_fixed_fd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572651,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_find_next_zero_area_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588465806,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_find_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588588079,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005362,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590066307,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591453206,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592696538,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594100625,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "drivers/firmware/efi/unaccepted_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595155658,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597036985,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597065421,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597167851,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597307852,
      "name": "find_next_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:173",
      "file": "lib/vsprintf.c",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496134208,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/context.c:check_and_switch_context",
        "arch/arm64/mm/context.c:check_and_switch_context",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "lib/sbitmap.c:__sbitmap_get_word",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_bitmap_alloc",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/firmware/ti_sci.c:ti_sci_get_free_resource",
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_get_event_idx",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_add",
        "drivers/perf/xgene_pmu.c:xgene_perf_add",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496134208,
      "name": "find_next_zero_bit",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290391536,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_get_ipi",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/events/uprobes.c:handle_swbp",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290391536,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275191936,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275191936,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224512,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224512,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159728,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159728,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208272,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208272,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312832,
      "name": "find_next_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:76",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_block_update_hint_alloc",
        "mm/percpu.c:pcpu_next_unpop",
        "fs/file.c:__alloc_fd",
        "fs/file.c:__alloc_fd",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "lib/bitmap.c:bitmap_find_next_zero_area_off",
        "lib/sbitmap.c:__sbitmap_get_word",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312832,
      "name": "find_next_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int * addr, long unsigned int size, long unsigned int offset)
```
</details>
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
