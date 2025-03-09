# Function: <code>__scsi_remove_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832384,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1101",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832384,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194640,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1276",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194640,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585389360,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1272",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389360,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474176,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1274",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474176,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905264,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1319",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905264,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152128,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1339",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152128,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293696,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1345",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293696,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586537104,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1357",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537104,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586685200,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685200,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587484016,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1386",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484016,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587551600,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1397",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587551600,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434000,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1403",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434000,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007504,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1428",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_free_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007504,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589367808,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1426",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589367808,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590937600,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1420",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590937600,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591281376,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1450",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281376,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628816,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1450",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628816,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499591168,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499591168,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232048628,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232048628,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292891952,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_free_host_dev",
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292891952,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276781620,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276781620,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375680,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375680,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216992,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216992,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586633168,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586633168,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void __scsi_remove_device(struct scsi_device * sdev)
```

```json
{
  "name": "__scsi_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586745712,
      "name": "__scsi_remove_device",
      "external": true,
      "loc": "drivers/scsi/scsi_sysfs.c:1366",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586745712,
      "name": "__scsi_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
