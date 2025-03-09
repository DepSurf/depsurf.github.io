# Function: <code>debugfs_create_file_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329552,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:399",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329552,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420352,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:399",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420352,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503952,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:433",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503952,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655264,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:436",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655264,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848384,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:459",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848384,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957088,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:460",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957088,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137552,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:473",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137552,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243728,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243728,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569648,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:474",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569648,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583691328,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:489",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691328,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715872,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:493",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715872,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076656,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:493",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076656,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668640,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:498",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668640,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350464,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:521",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350464,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580624,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:521",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "crypto/jitterentropy-testing.c:jent_testing_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580624,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585820368,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:528",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "kernel/sched/build_utility.c:sched_init_debug",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u8",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_add_host_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820368,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494967776,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494967776,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228375372,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228375372,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288847392,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dawr.c:dawr_force_setup",
        "arch/powerpc/kernel/eeh.c:eeh_init_proc",
        "arch/powerpc/kernel/eeh.c:eeh_init_proc",
        "arch/powerpc/kernel/eeh.c:eeh_init_proc",
        "arch/powerpc/kernel/eeh.c:eeh_init_proc",
        "arch/powerpc/kernel/eeh_cache.c:eeh_cache_debugfs_init",
        "arch/powerpc/mm/book3s64/hash_utils.c:__machine_initcall_pseries_hash64_debugfs",
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe",
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288847392,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274268788,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274268788,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583212464,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212464,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149616,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149616,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196496,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196496,
      "name": "debugfs_create_file_unsafe",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "debugfs_create_file_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290384,
      "name": "debugfs_create_file_unsafe",
      "external": true,
      "loc": "fs/debugfs/inode.c:475",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "kernel/panic.c:register_warn_debugfs",
        "mm/memory.c:fault_around_debugfs",
        "fs/debugfs/file.c:debugfs_create_u32_array",
        "fs/debugfs/file.c:debugfs_create_blob",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "fs/debugfs/file.c:debugfs_create_mode_unsafe",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290384,
      "name": "debugfs_create_file_unsafe",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct dentry * debugfs_create_file_unsafe(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```
</details>
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
