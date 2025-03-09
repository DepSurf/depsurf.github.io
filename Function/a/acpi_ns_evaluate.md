# Function: <code>acpi_ns_evaluate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681255,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681255,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005252,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005252,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584146698,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146698,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213953,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213953,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550528,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550528,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775032,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:48",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775032,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1093
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584876899,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:48",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876899,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1261
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585080785,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080785,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217133,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217133,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585922947,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922947,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044668,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044668,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585921512,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585921512,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586409629,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409629,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587659523,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659523,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1301
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964560,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964560,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1511
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254640,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254640,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1515
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589561264,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589561264,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1515
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497548764,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497548764,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083417,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083417,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998823,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998823,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168717,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168717,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```

```json
{
  "name": "acpi_ns_evaluate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274877,
      "name": "acpi_ns_evaluate",
      "external": true,
      "loc": "drivers/acpi/acpica/nseval.c:42",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274877,
      "name": "acpi_ns_evaluate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ns_evaluate(struct acpi_evaluate_info * info)
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
