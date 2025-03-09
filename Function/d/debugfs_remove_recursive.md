# Function: <code>debugfs_remove_recursive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582111712,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:584",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "drivers/pinctrl/core.c:pinctrl_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:fini",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/clk/clk.c:clk_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111712,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582327424,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:647",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "drivers/pinctrl/core.c:pinctrl_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327424,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582418224,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:647",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "drivers/pinctrl/core.c:pinctrl_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418224,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501792,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:681",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501792,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582653104,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:707",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653104,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582848432,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:730",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_exit",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848432,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582955744,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:733",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955744,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583136224,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:753",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136224,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583242400,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242400,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494966192,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_exit",
        "virt/kvm/kvm_main.c:kvm_vm_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_release",
        "virt/kvm/kvm_main.c:kvm_put_kvm",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/altera_edac.c:altr_edac_device_remove",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494966192,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228373212,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_remove",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_remove",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/mtd/mtdcore.c:cleanup_mtd",
        "drivers/mtd/mtdcore.c:del_mtd_device",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/usb/musb/musb_debugfs.c:musb_exit_debugfs",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "sound/soc/soc-core.c:snd_soc_exit",
        "sound/soc/soc-core.c:soc_cleanup_card_resources",
        "sound/soc/soc-core.c:soc_cleanup_component",
        "sound/soc/soc-dapm.c:snd_soc_dapm_free",
        "sound/soc/soc-pcm.c:dpcm_be_disconnect",
        "sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228373212,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288844000,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_window_free_dbgdir",
        "arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288844000,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274267280,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274267280,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211136,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211136,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583148288,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/nvdimm/btt.c:nd_btt_exit",
        "drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt",
        "drivers/nvdimm/btt.c:free_arenas",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148288,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195168,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195168,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void debugfs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288336,
      "name": "debugfs_remove_recursive",
      "external": true,
      "loc": "fs/debugfs/inode.c:755",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288336,
      "name": "debugfs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void debugfs_remove_recursive(struct dentry * dentry)
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
