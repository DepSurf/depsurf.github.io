# Function: <code>__scsi_iterate_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770048,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:945",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770048,
      "name": "__scsi_iterate_devices",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585131152,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:960",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131152,
      "name": "__scsi_iterate_devices",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325280,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:963",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325280,
      "name": "__scsi_iterate_devices",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412352,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:604",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412352,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585842704,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:584",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585842704,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586089792,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:584",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089792,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235968,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:584",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235968,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586479456,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479456,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586627248,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627248,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424099,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:554",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422528,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587493795,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:554",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_restart_operations",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587492224,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587375619,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:567",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373968,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587943235,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941584,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589297538,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:597",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296688,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590860418,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:597",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590859504,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591202738,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:753",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201824,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591550626,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:782",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:starget_for_each_device"
      ],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_unjam_host",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591549712,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499520712,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499520712,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231988016,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231988016,
      "name": "__scsi_iterate_devices",
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292810304,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport",
        "drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292810304,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276727578,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276727578,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317728,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317728,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159056,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/storvsc_drv.c:storvsc_host_scan",
        "drivers/scsi/storvsc_drv.c:storvsc_host_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159056,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575216,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575216,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct scsi_device * __scsi_iterate_devices(struct Scsi_Host * shost, struct scsi_device * prev)
```

```json
{
  "name": "__scsi_iterate_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687440,
      "name": "__scsi_iterate_devices",
      "external": true,
      "loc": "drivers/scsi/scsi.c:564",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_full",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_scan.c:do_scan_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687440,
      "name": "__scsi_iterate_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
