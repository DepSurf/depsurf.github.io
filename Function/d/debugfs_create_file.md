# Function: <code>debugfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113184,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:323",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/core.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/file.c:debugfs_create_mode",
        "fs/debugfs/file.c:debugfs_create_mode",
        "fs/debugfs/file.c:debugfs_create_mode",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/clk/clk.c:clk_debugfs_add_file",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113184,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582329494,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:360",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register",
        "mm/memory.c:fault_around_debugfs",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debugfs_add_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329440,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582420294,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:360",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register",
        "mm/memory.c:fault_around_debugfs",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debugfs_add_file",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420240,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582503894,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:394",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:debugfs_create_files",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debugfs_add_file",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:pm_genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503840,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655206,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:397",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/panic.c:register_warn_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:debugfs_create_files",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debugfs_add_file",
        "drivers/clk/clk.c:clk_debug_create_one",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655152,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582848339,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:420",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/panic.c:register_warn_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:debugfs_create_files",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848272,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582957043,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:421",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/panic.c:register_warn_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956976,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137507,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:434",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137440,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243683,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243616,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569603,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:435",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_bw",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569536,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691290,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:450",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/power/energy_model.c:em_debug_create_pd",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_bw",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/ras/cec.c:create_debugfs_nodes",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691216,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715834,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:454",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715760,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584076602,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:454",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slub.c:debugfs_slab_add",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076528,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584668570,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:459",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:debugfs_slab_add",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668480,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585350378,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:482",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:debugfs_slab_add",
        "mm/slub.c:debugfs_slab_add",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/kfence/core.c:kfence_debugfs_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350272,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585580517,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:482",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:debugfs_slab_add",
        "mm/slub.c:debugfs_slab_add",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/power/domain.c:genpd_debug_add",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580432,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585820261,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:489",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/dma/swiotlb.c:swiotlb_create_default_debugfs",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmscan.c:init_lru_gen",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:debugfs_slab_add",
        "mm/slub.c:debugfs_slab_add",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_control",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/clk/clk-fractional-divider.c:clk_fd_debug_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/pmdomain/core.c:genpd_debug_init",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/pmdomain/core.c:genpd_debug_add",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_register",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_create_files",
        "drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add",
        "drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs",
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint",
        "drivers/opp/debugfs.c:opp_debug_create_one",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init",
        "drivers/interconnect/core.c:icc_init",
        "drivers/interconnect/core.c:icc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820176,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494967692,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_probe",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/firmware/ti_sci.c:ti_sci_probe",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494967520,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228375308,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init",
        "arch/arm/mach-omap2/pm-debug.c:pwrdms_setup",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/memblock.c:memblock_init_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/musb/musb_debugfs.c:musb_init_debugfs",
        "drivers/usb/musb/musb_debugfs.c:musb_init_debugfs",
        "drivers/usb/musb/musb_debugfs.c:musb_init_debugfs",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/firmware/tegra/bpmp-debugfs.c:bpmp_populate_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "sound/soc/soc-core.c:snd_soc_init",
        "sound/soc/soc-core.c:snd_soc_init",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_widgets",
        "sound/soc/soc-dapm.c:snd_soc_dapm_debugfs_init",
        "sound/soc/soc-pcm.c:soc_dpcm_debugfs_add",
        "sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_create",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228375212,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288847312,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/powerpc/kernel/setup_64.c:rfi_flush_debugfs_init",
        "arch/powerpc/kernel/security.c:count_cache_flush_debugfs_init",
        "arch/powerpc/kernel/security.c:stf_barrier_debugfs_init",
        "arch/powerpc/kernel/security.c:barrier_nospec_debugfs_init",
        "arch/powerpc/kernel/fadump.c:setup_fadump",
        "arch/powerpc/platforms/powernv/opal-lpc.c:opal_lpc_debugfs_create_type",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "arch/powerpc/platforms/powernv/memtrace.c:__machine_initcall_powernv_memtrace_init",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir",
        "arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir",
        "arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vpa_debugfs_init",
        "arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init",
        "arch/powerpc/xmon/xmon.c:setup_xmon_dbgfs",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/memblock.c:memblock_init_debugfs",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288847216,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274268722,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/ras/debugfs.c:ras_add_daemon_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274268588,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583212419,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212352,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583149571,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149504,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583196451,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196384,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct dentry * debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583290339,
      "name": "debugfs_create_file",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_file_size"
      ],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling",
        "arch/x86/mm/pkeys.c:create_init_pkru_value",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_ptc_init",
        "kernel/sched/debug.c:sched_init_debug",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/main.c:pm_debugfs_init",
        "kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_create_buf_file_callback",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/vmstat.c:extfrag_debug_init",
        "mm/slab_common.c:memcg_slabinfo_init",
        "mm/huge_memory.c:split_huge_pages_debugfs",
        "fs/debugfs/file.c:debugfs_create_devm_seqfile",
        "fs/debugfs/file.c:debugfs_create_regset32",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_init",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs",
        "drivers/gpio/gpiolib.c:gpiolib_debugfs_init",
        "drivers/pwm/core.c:pwm_debugfs_init",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/clk/clk.c:clk_debug_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/char/virtio_console.c:add_port",
        "drivers/base/component.c:component_master_add_with_match",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/power/wakeup.c:wakeup_sources_debugfs_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/power/domain.c:genpd_debug_init",
        "drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file",
        "drivers/ras/debugfs.c:ras_add_daemon_trace",
        "drivers/ras/cec.c:cec_init",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290272,
      "name": "debugfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
