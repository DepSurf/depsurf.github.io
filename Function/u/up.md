# Function: <code>up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671936,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:suspend_console",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671936,
      "name": "up",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690752,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:suspend_console",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690752,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718464,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:suspend_console",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718464,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714320,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:179",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714320,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746928,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:179",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746928,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781296,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:179",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781296,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827872,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:179",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827872,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859200,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859200,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907888,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_call",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907888,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951760,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/printk/printk.c:console_unlock",
        "kernel/seccomp.c:seccomp_notify_recv",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951760,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940080,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/printk/printk.c:console_unlock",
        "kernel/seccomp.c:seccomp_notify_recv",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940080,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947792,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/seccomp.c:seccomp_notify_recv",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947792,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076864,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:182",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/printk/printk.c:console_unlock",
        "kernel/seccomp.c:seccomp_notify_recv",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076864,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212640,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:183",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/seccomp.c:seccomp_notify_recv",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212640,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596475072,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:183",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/seccomp.c:seccomp_notify_recv",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivar_trylock",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivars_register",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596475072,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597016656,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:183",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/module/kmod.c:__request_module",
        "kernel/seccomp.c:seccomp_notify_recv",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivar_trylock",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivars_register",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597016656,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597946000,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:183",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base",
        "kernel/module/kmod.c:__request_module",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__set_swap_bios_limit",
        "drivers/md/dm.c:clone_endio",
        "drivers/firmware/efi/vars.c:efivar_trylock",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivars_register",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_acpi_prm_handler",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597946000,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491108680,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491108680,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225112700,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-vexpress/spc.c:spc_set_rate",
        "arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225112700,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284000768,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-async.c:opal_async_release_token",
        "arch/powerpc/platforms/powernv/opal-async.c:opal_async_get_token_interruptible",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284000768,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271689302,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271689302,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880000,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880000,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814992,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/hv/vmbus_drv.c:vmbus_free_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_allocate_mmio",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814992,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868160,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868160,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void up(struct semaphore * sem)
```

```json
{
  "name": "up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913584,
      "name": "up",
      "external": true,
      "loc": "kernel/locking/semaphore.c:178",
      "file": "kernel/locking/semaphore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_call",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "fs/pstore/platform.c:pstore_dump",
        "drivers/acpi/osl.c:acpi_os_signal_semaphore",
        "drivers/firmware/efi/vars.c:efivars_unregister",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_remove",
        "drivers/firmware/efi/vars.c:efivar_entry_add",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/vars.c:efivar_init",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/core/netpoll.c:netpoll_poll_enable",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913584,
      "name": "up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
