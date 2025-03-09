# Function: <code>debugfs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112928,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:409",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/backing-dev.c:bdi_register",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112928,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582328640,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:469",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328640,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419440,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:469",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419440,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503040,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:503",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503040,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582654352,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:506",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654352,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847456,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:529",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_init",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847456,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956160,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:532",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956160,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:545",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137796,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583136624,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243972,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583242800,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:536",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:zswap_debugfs_init",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_supplies",
        "drivers/opp/debugfs.c:opp_debug_create_bw",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570684,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583568656,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:551",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:zswap_debugfs_init",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_supplies",
        "drivers/opp/debugfs.c:opp_debug_create_bw",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591360623,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583690032,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:555",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303448,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583714576,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:555",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:slab_debugfs_init",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592289539,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071584075264,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:565",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:slab_debugfs_init",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/hte/hte.c:hte_register_chip",
        "drivers/hte/hte.c:__hte_req_ts",
        "drivers/hte/hte.c:hte_subsys_dbgfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594071624,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584667184,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:588",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:slab_debugfs_init",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/hte/hte.c:hte_register_chip",
        "drivers/hte/hte.c:__hte_req_ts",
        "drivers/hte/hte.c:hte_subsys_dbgfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596091989,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585350880,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:588",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:zswap_setup",
        "mm/slub.c:slab_debugfs_init",
        "mm/slub.c:debugfs_slab_add",
        "crypto/jitterentropy-testing.c:jent_testing_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/hte/hte.c:hte_register_chip",
        "drivers/hte/hte.c:__hte_req_ts",
        "drivers/hte/hte.c:hte_subsys_dbgfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596615353,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585581040,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:595",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs",
        "arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_debug_init",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/pool.c:dma_atomic_pool_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/slub.c:slab_debugfs_init",
        "mm/slub.c:debugfs_slab_add",
        "mm/zswap.c:zswap_debugfs_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/pmdomain/core.c:genpd_debug_init",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_crtc_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_init",
        "drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add",
        "drivers/accel/drm_accel.c:accel_core_init",
        "drivers/gpu/drm/bridge/panel.c:panel_bridge_debugfs_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_chardev.c:ptp_open",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/hte/hte.c:hte_register_chip",
        "drivers/hte/hte.c:__hte_req_ts",
        "drivers/hte/hte.c:hte_subsys_dbgfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597521202,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585819024,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494966624,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494966624,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228374320,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:pwrdms_setup",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_class_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/usb/musb/musb_debugfs.c:musb_init_debugfs",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:bpmp_populate_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "sound/soc/soc-core.c:snd_soc_init",
        "sound/soc/soc-core.c:snd_soc_instantiate_card",
        "sound/soc/soc-core.c:soc_probe_component",
        "sound/soc/soc-core.c:soc_probe_component",
        "sound/soc/soc-dapm.c:snd_soc_dapm_debugfs_init",
        "sound/soc/soc-pcm.c:soc_dpcm_debugfs_add",
        "sound/soc/soc-pcm.c:dpcm_add_paths",
        "sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_create",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228374320,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288846032,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:powerpc_debugfs_init",
        "arch/powerpc/platforms/powernv/opal-lpc.c:__machine_initcall_powernv_opal_lpc_init_debugfs",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup",
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe",
        "arch/powerpc/platforms/powernv/memtrace.c:__machine_initcall_powernv_memtrace_init",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_instance_init_dbgdir",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir",
        "arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vpa_debugfs_init",
        "arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288846032,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274267804,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/ras/debugfs.c:ras_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274267804,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212708,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583211536,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/nvdimm/btt.c:nd_btt_init",
        "drivers/nvdimm/btt.c:btt_debugfs_init",
        "drivers/nvdimm/btt.c:btt_debugfs_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149860,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583148688,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196740,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583195568,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_create_dir",
      "external": true,
      "loc": "fs/debugfs/inode.c:547",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/dma/swiotlb.c:swiotlb_create_debugfs",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/frontswap.c:init_frontswap",
        "mm/zswap.c:init_zswap",
        "mm/cleancache.c:init_cleancache",
        "block/blk-core.c:blk_dev_init",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/acpi/debugfs.c:acpi_debugfs_init",
        "drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:rdev_init_debugfs",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:init",
        "drivers/base/component.c:component_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/usb/common/common.c:usb_common_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/opp/debugfs.c:opp_debug_init",
        "drivers/opp/debugfs.c:opp_debug_register",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/ras/debugfs.c:ras_debugfs_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290628,
      "name": "debugfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583289456,
      "name": "debugfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
