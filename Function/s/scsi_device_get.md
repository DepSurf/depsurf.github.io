# Function: <code>scsi_device_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584769728,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:912",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769728,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585130832,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:927",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130832,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324960,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:930",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324960,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412016,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:571",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412016,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585842368,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:551",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585842368,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586089456,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:551",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089456,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235632,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:551",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235632,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586479120,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479120,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626912,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626912,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587422160,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:521",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_lib.c:scsi_single_lun_run",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422160,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587491856,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:521",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_lib.c:scsi_single_lun_run",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491856,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373600,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:534",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373600,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587941216,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:529",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941216,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589295904,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:562",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589295904,
      "name": "scsi_device_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590855952,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:562",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855952,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591197936,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:718",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591197936,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591544928,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:747",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:starget_for_each_device",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591544928,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499518824,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499518824,
      "name": "scsi_device_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231987668,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:scsi_disk_get",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231987668,
      "name": "scsi_device_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292809696,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:scsi_disk_get",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292809696,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276727260,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sd.c:scsi_disk_get",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276727260,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317392,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317392,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158720,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158720,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574880,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574880,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int scsi_device_get(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687104,
      "name": "scsi_device_get",
      "external": true,
      "loc": "drivers/scsi/scsi.c:531",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_check_events",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687104,
      "name": "scsi_device_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
