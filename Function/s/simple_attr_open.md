# Function: <code>simple_attr_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156144,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:758",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "drivers/cpufreq/intel_pstate.c:fops_pid_param_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156144,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321392,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:786",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/cpufreq/intel_pstate.c:fops_pid_param_open",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321392,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400576,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:794",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/cpufreq/intel_pstate.c:fops_pid_param_open",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400576,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455840,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:795",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/cpufreq/intel_pstate.c:fops_pid_param_open",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:count_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open",
        "drivers/ras/cec.c:pfn_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455840,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597824,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:795",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:count_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open",
        "drivers/ras/cec.c:pfn_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597824,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755440,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:795",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:count_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open",
        "drivers/ras/cec.c:pfn_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755440,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841968,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:795",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:count_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open",
        "drivers/ras/cec.c:pfn_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841968,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966528,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:814",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966528,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039520,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039520,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275696,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:888",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275696,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582325824,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:890",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325824,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353760,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:893",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353760,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674848,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:902",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674848,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218992,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:929",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218992,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796992,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:930",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "kernel/dma/swiotlb.c:fops_io_tlb_used_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_err_state_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796992,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014816,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:925",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "kernel/dma/swiotlb.c:fops_io_tlb_hiwater_open",
        "kernel/dma/swiotlb.c:fops_io_tlb_used_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_err_state_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014816,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227152,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:1195",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "kernel/dma/swiotlb.c:fops_io_tlb_hiwater_open",
        "kernel/dma/swiotlb.c:fops_io_tlb_used_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/clk.c:clk_phase_fops_open",
        "drivers/clk/clk.c:clk_rate_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open",
        "drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_caps2_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_caps_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_err_state_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227152,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493564976,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:vcpu_stat_fops_open",
        "virt/kvm/kvm_main.c:vm_stat_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493564976,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227113576,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pm-debug.c:pm_dbg_option_fops_open",
        "arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/clk/tegra/clk-dfll.c:rate_fops_open",
        "drivers/clk/tegra/clk-dfll.c:lock_fops_open",
        "drivers/clk/tegra/clk-dfll.c:enable_fops_open",
        "drivers/power/avs/smartreflex.c:pm_sr_fops_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open",
        "drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_fops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227113576,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287145328,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup_64.c:fops_rfi_flush_open",
        "arch/powerpc/kernel/security.c:fops_count_cache_flush_open",
        "arch/powerpc/kernel/security.c:fops_stf_barrier_open",
        "arch/powerpc/kernel/security.c:fops_barrier_nospec_open",
        "arch/powerpc/kernel/eeh.c:eeh_enable_dbgfs_ops_open",
        "arch/powerpc/mm/book3s64/hash_utils.c:fops_hpt_order_open",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_diag_data_fops_open",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_inbB_open",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_inbA_open",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_outb_open",
        "arch/powerpc/platforms/powernv/opal-imc.c:fops_imc_x64_open",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_fops_open",
        "arch/powerpc/xmon/xmon.c:xmon_dbgfs_ops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287145328,
      "name": "simple_attr_open",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273222644,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273222644,
      "name": "simple_attr_open",
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008256,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008256,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945824,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945824,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999536,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999536,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int simple_attr_open(struct inode * inode, struct file * file, int (*)(void *, u64 *) get, int (*)(void *, u64) set, const char * fmt)
```

```json
{
  "name": "simple_attr_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070736,
      "name": "simple_attr_open",
      "external": true,
      "loc": "fs/libfs.c:852",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open",
        "kernel/panic.c:clear_warn_once_fops_open",
        "mm/memory.c:fault_around_bytes_fops_open",
        "mm/huge_memory.c:split_huge_pages_fops_open",
        "fs/debugfs/file.c:fops_atomic_t_wo_open",
        "fs/debugfs/file.c:fops_atomic_t_ro_open",
        "fs/debugfs/file.c:fops_atomic_t_open",
        "fs/debugfs/file.c:fops_size_t_wo_open",
        "fs/debugfs/file.c:fops_size_t_ro_open",
        "fs/debugfs/file.c:fops_size_t_open",
        "fs/debugfs/file.c:fops_x64_wo_open",
        "fs/debugfs/file.c:fops_x64_ro_open",
        "fs/debugfs/file.c:fops_x64_open",
        "fs/debugfs/file.c:fops_x32_wo_open",
        "fs/debugfs/file.c:fops_x32_ro_open",
        "fs/debugfs/file.c:fops_x32_open",
        "fs/debugfs/file.c:fops_x16_wo_open",
        "fs/debugfs/file.c:fops_x16_ro_open",
        "fs/debugfs/file.c:fops_x16_open",
        "fs/debugfs/file.c:fops_x8_wo_open",
        "fs/debugfs/file.c:fops_x8_ro_open",
        "fs/debugfs/file.c:fops_x8_open",
        "fs/debugfs/file.c:fops_ulong_wo_open",
        "fs/debugfs/file.c:fops_ulong_ro_open",
        "fs/debugfs/file.c:fops_ulong_open",
        "fs/debugfs/file.c:fops_u64_wo_open",
        "fs/debugfs/file.c:fops_u64_ro_open",
        "fs/debugfs/file.c:fops_u64_open",
        "fs/debugfs/file.c:fops_u32_wo_open",
        "fs/debugfs/file.c:fops_u32_ro_open",
        "fs/debugfs/file.c:fops_u32_open",
        "fs/debugfs/file.c:fops_u16_wo_open",
        "fs/debugfs/file.c:fops_u16_ro_open",
        "fs/debugfs/file.c:fops_u16_open",
        "fs/debugfs/file.c:fops_u8_wo_open",
        "fs/debugfs/file.c:fops_u8_ro_open",
        "fs/debugfs/file.c:fops_u8_open",
        "drivers/mmc/core/debugfs.c:mmc_clock_fops_open",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open",
        "drivers/ras/cec.c:action_threshold_ops_open",
        "drivers/ras/cec.c:decay_interval_ops_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070736,
      "name": "simple_attr_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
