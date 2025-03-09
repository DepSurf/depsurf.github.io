# Function: <code>acpi_os_execute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538431,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1120",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538431,
      "name": "acpi_os_execute",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859396,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1036",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859396,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998420,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1031",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998420,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584046944,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1030",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046944,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313104,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1040",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313104,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1045",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536579,
      "name": "acpi_os_execute.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584533264,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1050",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633795,
      "name": "acpi_os_execute.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584630592,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1036",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833582,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584830288,
      "name": "acpi_os_execute",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969310,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584966016,
      "name": "acpi_os_execute",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665062,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585661568,
      "name": "acpi_os_execute",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1060",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430542,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585787248,
      "name": "acpi_os_execute",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1061",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591371907,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585667616,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1061",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406331,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586147104,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1063",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594271936,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071587379696,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629648,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1063",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629648,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917392,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1063",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/button.c:acpi_button_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917392,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589213456,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1060",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/button.c:acpi_button_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589213456,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497377312,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497377312,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917220,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584913312,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823140,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584819248,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920894,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584917600,
      "name": "acpi_os_execute",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_os_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_execute",
      "external": true,
      "loc": "drivers/acpi/osl.c:1056",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_device_fixed_event",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027038,
      "name": "acpi_os_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585023744,
      "name": "acpi_os_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void * context)
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
