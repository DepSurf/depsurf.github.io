# Function: <code>scsi_device_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770000,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:937",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770000,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585131104,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:952",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131104,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325232,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:955",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325232,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412304,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:596",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412304,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585842656,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:576",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585842656,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586089744,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:576",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089744,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235920,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:576",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235920,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586479408,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479408,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586627200,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627200,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587422272,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:546",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_single_lun_run",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422272,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587491968,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:546",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_single_lun_run",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491968,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587373712,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:559",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373712,
      "name": "scsi_device_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587941328,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:554",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941328,
      "name": "scsi_device_put",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589296016,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:587",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:sr_block_release",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296016,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590856096,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:587",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:sr_block_release",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590856096,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591198080,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:743",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:sr_block_release",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591198080,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591545072,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:772",
      "file": "drivers/scsi/scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_lib.c:scsi_host_unblock",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sr.c:sr_block_release",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591545072,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499518936,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499518936,
      "name": "scsi_device_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231987964,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231987964,
      "name": "scsi_device_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292810208,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292810208,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276727520,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276727520,
      "name": "scsi_device_put",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317680,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317680,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159008,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/storvsc_drv.c:storvsc_remove_lun",
        "drivers/scsi/storvsc_drv.c:storvsc_device_scan",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159008,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575168,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575168,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void scsi_device_put(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687392,
      "name": "scsi_device_put",
      "external": true,
      "loc": "drivers/scsi/scsi.c:556",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_proc.c:proc_scsi_write",
        "drivers/scsi/sd.c:scsi_disk_put",
        "drivers/scsi/sr.c:scsi_cd_put",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687392,
      "name": "scsi_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
