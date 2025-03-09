# Function: <code>acpi_os_signal_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540576,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1329",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540576,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861531,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1262",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861531,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000607,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1257",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000607,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049392,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1256",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049392,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315600,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1266",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315600,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535648,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1271",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535648,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632864,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1277",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632864,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832576,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1263",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832576,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968304,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968304,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663904,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663904,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789584,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1287",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789584,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669952,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1287",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669952,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1287",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406533,
      "name": "acpi_os_signal_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586149520,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1289",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272118,
      "name": "acpi_os_signal_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587382192,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1289",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596218260,
      "name": "acpi_os_signal_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588632464,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1289",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596744967,
      "name": "acpi_os_signal_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588920208,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597653515,
      "name": "acpi_os_signal_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589216480,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497381928,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497381928,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916496,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916496,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822416,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822416,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919888,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919888,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```

```json
{
  "name": "acpi_os_signal_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026032,
      "name": "acpi_os_signal_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1283",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026032,
      "name": "acpi_os_signal_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units)
```
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
