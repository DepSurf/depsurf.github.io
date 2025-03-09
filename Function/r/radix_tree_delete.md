# Function: <code>radix_tree_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970752,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1427",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swap_state.c:__delete_from_swap_cache",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/block/brd.c:brd_free_pages",
        "drivers/block/brd.c:brd_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970752,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259520,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1580",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swap_state.c:__delete_from_swap_cache",
        "fs/dax.c:dax_delete_mapping_entry",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/block/brd.c:brd_free_pages",
        "drivers/block/brd.c:brd_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259520,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375728,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1899",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_invalidate_mapping_entry",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375728,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224816,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:2067",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224816,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774880,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:2064",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/memremap.c:pgmap_radix_release",
        "mm/backing-dev.c:cgwb_kill",
        "mm/vmalloc.c:free_vmap_block",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774880,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153536,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:2065",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/memremap.c:pgmap_radix_release",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153536,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386080,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1467",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386080,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843104,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843104,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069200,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069200,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066352,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1446",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "mm/vmalloc.c:free_vmap_block",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:free_pwms",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single",
        "net/mptcp/token.c:mptcp_token_destroy",
        "net/mptcp/token.c:mptcp_token_destroy_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066352,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215680,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1446",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:free_pwms",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215680,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098528,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1447",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098528,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546784,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1447",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546784,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702512,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1447",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702512,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595864256,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1447",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595864256,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596381600,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1445",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596381600,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597276848,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1445",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597276848,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503847160,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503847160,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236466720,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/usb/host/xhci-mem.c:xhci_remove_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236466720,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297701296,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "mm/backing-dev.c:cgwb_kill",
        "mm/vmalloc.c:free_vmap_block",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297701296,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279737122,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279737122,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671456,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671456,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397280,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397280,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114832,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590114832,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * radix_tree_delete(struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165216,
      "name": "radix_tree_delete",
      "external": true,
      "loc": "lib/radix-tree.c:1454",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/backing-dev.c:cgwb_kill",
        "block/blk-ioc.c:ioc_destroy_icq",
        "block/blk-cgroup.c:blkg_destroy",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165216,
      "name": "radix_tree_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
</li>
</ul>
</details>
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
