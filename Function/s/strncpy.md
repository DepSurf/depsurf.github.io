# Function: <code>strncpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strncpy(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979984,
      "name": "strncpy",
      "external": true,
      "loc": "lib/string.c:112",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/module.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/exec.c:get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/kernfs/symlink.c:kernfs_iop_follow_link",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:choose_lsm",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "lib/kobject.c:kobject_get_path",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/battery.c:extract_package",
        "drivers/acpi/battery.c:extract_package",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu",
        "drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/leds/led-triggers.c:led_trigger_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/socket.c:sockfs_getxattr",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979984,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
char * strncpy(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269152,
      "name": "strncpy",
      "external": true,
      "loc": "lib/string.c:112",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/cgroup.c:cgroup_file_name",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/exec.c:get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/kernfs/symlink.c:kernfs_iop_get_link",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:choose_lsm",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "lib/kobject.c:kobject_get_path",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/battery.c:extract_package",
        "drivers/acpi/battery.c:extract_package",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/lightnvm/sysblk.c:nvm_get_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_write_and_verify",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/socket.c:sockfs_getxattr",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269152,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
char * strncpy(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387920,
      "name": "strncpy",
      "external": true,
      "loc": "lib/string.c:112",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/cgroup.c:cgroup_file_name",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/exec.c:get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/kernfs/symlink.c:kernfs_iop_get_link",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:choose_lsm",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "lib/kobject.c:kobject_get_path",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/battery.c:extract_package",
        "drivers/acpi/battery.c:extract_package",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/lightnvm/sysblk.c:nvm_get_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_write_and_verify",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387920,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596314060,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:206",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/exec.c:get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:set_lsm_of_current",
        "security/security.c:choose_display_lsm",
        "security/security.c:choose_lsm",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/aead.c:crypto_aead_report",
        "crypto/aead.c:crypto_aead_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/ahash.c:crypto_ahash_report",
        "crypto/shash.c:crypto_shash_report",
        "crypto/akcipher.c:crypto_akcipher_report",
        "crypto/kpp.c:crypto_kpp_report",
        "crypto/acompress.c:crypto_acomp_report",
        "crypto/scompress.c:crypto_scomp_report",
        "crypto/rng.c:crypto_rng_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key",
        "lib/kobject.c:kobject_get_path"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243760,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602631611,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:238",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:set_lsm_of_current",
        "security/security.c:choose_display_lsm",
        "security/security.c:choose_lsm",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/aead.c:crypto_aead_report",
        "crypto/aead.c:crypto_aead_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/ahash.c:crypto_ahash_report",
        "crypto/shash.c:crypto_shash_report",
        "crypto/akcipher.c:crypto_akcipher_report",
        "crypto/kpp.c:crypto_kpp_report",
        "crypto/acompress.c:crypto_acomp_report",
        "crypto/scompress.c:crypto_scomp_report",
        "crypto/rng.c:crypto_rng_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key",
        "lib/kobject.c:kobject_get_path"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795184,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602800206,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:239",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/security.c:choose_lsm",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "crypto/aead.c:crypto_aead_report",
        "crypto/aead.c:crypto_aead_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_givcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/ablkcipher.c:crypto_ablkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/blkcipher.c:crypto_blkcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/skcipher.c:crypto_skcipher_report",
        "crypto/ahash.c:crypto_ahash_report",
        "crypto/shash.c:crypto_shash_report",
        "crypto/akcipher.c:crypto_akcipher_report",
        "crypto/kpp.c:crypto_kpp_report",
        "crypto/acompress.c:crypto_acomp_report",
        "crypto/scompress.c:crypto_scomp_report",
        "crypto/rng.c:crypto_rng_report",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key",
        "lib/kobject.c:kobject_get_path"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173376,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604594317,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:246",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_getstr",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/pinctrl/pinconf.c:pinconf_dbg_config_write",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403296,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604689971,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:253",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_parse_version",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/elevator.c:elevator_setup",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/pci.c:pci_set_resource_alignment_param",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859328,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604702267,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085120,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609007281,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:300",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:add_to_key",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib.c:gpio_desc_to_lineinfo",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:uevent_notify",
        "drivers/power/supply/charger-manager.c:uevent_notify",
        "drivers/power/supply/charger-manager.c:uevent_notify",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082912,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612071391,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:294",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:save_cmdstr",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:add_to_key",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232080,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614209602,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:30",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_parts",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114960,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615127686,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:30",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:do_mount_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563632,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
char * strncpy(const char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616889668,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:81",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:do_mount_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module/main.c:resolve_symbol",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/acpi/battery.c:extract_package",
        "drivers/acpi/battery.c:extract_package",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586716704,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
char * strncpy(const char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627480864,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:136",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:do_mount_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module/main.c:resolve_symbol",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:add_to_key",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/verifier.c:reg_type_str",
        "fs/proc/vmcore.c:vmcoredd_write_header",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/acpi/battery.c:extract_package",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595878752,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
char * strncpy(const char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619224384,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:143",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:do_mount_root",
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module/main.c:resolve_symbol",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:add_to_key",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/verifier.c:reg_type_str",
        "fs/proc/vmcore.c:vmcoredd_write_header",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/cmdline.c:add_part",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_parts",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596396128,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
char * strncpy(const char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621514192,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/fortify-string.h:139",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:do_mount_root",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module/main.c:resolve_symbol",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace.c:trace_save_cmdline",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:add_to_key",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/bpf/log.c:reg_type_str",
        "fs/proc/vmcore.c:vmcoredd_write_header",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597291360,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510876880,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj_region",
        "drivers/bus/fsl-mc/dprc.c:dprc_set_obj_irq",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/clk/zynqmp/clkc.c:zynqmp_get_clock_info",
        "drivers/clk/zynqmp/clkc.c:zynqmp_get_clock_name",
        "drivers/soc/qcom/cmd-db.c:cmd_db_get_header",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/firmware/ti_sci.c:ti_sci_probe",
        "drivers/of/base.c:of_alias_scan",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863080,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243376152,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/soc/qcom/cmd-db.c:cmd_db_get_header",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show",
        "drivers/of/base.c:of_alias_scan",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236490432,
      "name": "strncpy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302507392,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/of/base.c:of_alias_scan",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282851952,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 0
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
char * strncpy(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279759222,
      "name": "strncpy",
      "external": true,
      "loc": "lib/string.c:114",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/of/base.c:of_alias_scan",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759222,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604628555,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687376,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119989,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413168,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604706363,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130752,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * strncpy(char * p, const char * q, __kernel_size_t size)
```

```json
{
  "name": "strncpy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604706379,
      "name": "strncpy",
      "external": true,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/xen/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:param_set_action",
        "kernel/sys.c:parse_compat_uts_machine",
        "kernel/power/hibernate.c:resume_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:console_setup",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:resolve_symbol",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_stack.c:enable_stacktrace",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:cond_snapshot_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:__save_error_info",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/unicode/utf8-core.c:utf8_load",
        "security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok",
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/bsg.c:bsg_open",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_infoframe_log",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/video/hdmi.c:hdmi_spd_infoframe_init",
        "drivers/acpi/osi.c:acpi_osi_setup",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dax/bus.c:do_id_store",
        "drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo",
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access",
        "drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/edac/edac_mc_sysfs.c:dimmdev_label_store",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit",
        "net/ipv4/tcp_cong.c:tcp_get_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181136,
      "name": "strncpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * p</code>
</li>
<li>
<b>Param added. </b>
<code>const char * q</code>
</li>
<li>
<b>Param added. </b>
<code>__kernel_size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>char * dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * p</code> ➡️ <code>const char * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char * src</code>
</li>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>char * p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * q</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
</ul>
</details>
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
