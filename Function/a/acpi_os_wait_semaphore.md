# Function: <code>acpi_os_wait_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540473,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1284",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540473,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861428,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1217",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861428,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000504,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1212",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface_handler",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000504,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049280,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1211",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049280,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315200,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1221",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315200,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535232,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1226",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535232,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632448,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1232",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632448,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832160,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1218",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832160,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967888,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967888,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663488,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663488,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789168,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1242",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789168,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669536,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1242",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669536,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1242",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406512,
      "name": "acpi_os_wait_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586149072,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1244",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272097,
      "name": "acpi_os_wait_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587381744,
      "name": "acpi_os_wait_semaphore",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1244",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596218239,
      "name": "acpi_os_wait_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588632000,
      "name": "acpi_os_wait_semaphore",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1244",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596744946,
      "name": "acpi_os_wait_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588919744,
      "name": "acpi_os_wait_semaphore",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_remove_interface",
        "drivers/acpi/acpica/utxface.c:acpi_install_interface",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597653494,
      "name": "acpi_os_wait_semaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589216016,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497381768,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497381768,
      "name": "acpi_os_wait_semaphore",
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916384,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916384,
      "name": "acpi_os_wait_semaphore",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822304,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822304,
      "name": "acpi_os_wait_semaphore",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919472,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919472,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```

```json
{
  "name": "acpi_os_wait_semaphore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585025616,
      "name": "acpi_os_wait_semaphore",
      "external": true,
      "loc": "drivers/acpi/osl.c:1238",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation",
        "drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate",
        "drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces",
        "drivers/acpi/acpica/utxface.c:acpi_update_interfaces",
        "drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_method_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585025616,
      "name": "acpi_os_wait_semaphore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout)
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
