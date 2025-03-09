# Function: <code>simple_strtol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:89",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "init/do_mounts_rd.c:prompt_ramdisk",
        "init/do_mounts_rd.c:ramdisk_start_setup",
        "kernel/audit.c:audit_enable",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_options",
        "lib/parser.c:match_token",
        "lib/parser.c:match_number",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_class.c:timeout_store",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/brd.c:ramdisk_size",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988368,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583280704,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:95",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "init/do_mounts_rd.c:ramdisk_start_setup",
        "init/do_mounts_rd.c:prompt_ramdisk",
        "kernel/audit.c:audit_enable",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf",
        "lib/parser.c:match_number",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/brd.c:ramdisk_size",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280704,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583399456,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:95",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/audit.c:audit_enable",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf",
        "lib/parser.c:match_number",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399456,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588255632,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:96",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/audit.c:audit_enable",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255632,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588807680,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:98",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807680,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589183776,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:97",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/deadline-iosched.c:deadline_fifo_batch_store",
        "block/deadline-iosched.c:deadline_front_merges_store",
        "block/deadline-iosched.c:deadline_writes_starved_store",
        "block/deadline-iosched.c:deadline_write_expire_store",
        "block/deadline-iosched.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/core.c:device_store_int",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589183776,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589414288,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:98",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414288,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589871264,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589871264,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590097168,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097168,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585090480,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:103",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090480,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239584,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:103",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "lib/cmdline.c:get_options",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239584,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124912,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:117",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124912,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585574256,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:118",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574256,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586726496,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:122",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726496,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595889184,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:123",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595889184,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596406576,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:123",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/fbcon.c:fb_console_setup",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596406576,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597304288,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:125",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "lib/parser.c:match_number",
        "lib/parser.c:match_one",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597304288,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503877496,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503877496,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236507636,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_number",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236507636,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297742176,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "arch/powerpc/kernel/sysfs.c:setup_smt_snooze_delay",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297742176,
      "name": "simple_strtol",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279771830,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279771830,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589699424,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589699424,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589425216,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425216,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590142800,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142800,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int simple_strtol(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590193200,
      "name": "simple_strtol",
      "external": true,
      "loc": "lib/vsprintf.c:100",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:load_ramdisk",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/watchdog.c:softlockup_all_cpu_backtrace_setup",
        "kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/main.c:ecryptfs_parse_options",
        "fs/ecryptfs/crypto.c:ecryptfs_from_hex",
        "crypto/algboss.c:cryptomgr_notify",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/parser.c:match_token",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/video/fbdev/core/modedb.c:fb_find_mode",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback.c:timeout_store",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/block/loop.c:max_loop_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup",
        "lib/cmdline.c:get_options",
        "lib/cmdline.c:get_option",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590193200,
      "name": "simple_strtol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
