# Function: <code>__scsi_execute</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585357200,
      "name": "__scsi_execute",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_execute_req_flags",
        "drivers/scsi/scsi_lib.c:scsi_execute_req_flags",
        "drivers/scsi/scsi_lib.c:scsi_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357200,
      "name": "__scsi_execute.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586259152,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:250",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:__scsi_scan_target",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259152,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586503232,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503232,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651120,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651120,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447888,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:241",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_get_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447888,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587515952,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:240",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_get_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515952,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397568,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:206",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397568,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587969280,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_resume_runtime",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969280,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589332752,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:209",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_get_vpd_size",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_resume_runtime",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332752,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, blk_opf_t flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:207",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_get_vpd_size",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_resume_runtime",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596259967,
      "name": "__scsi_execute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590899008,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499549216,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499549216,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232012712,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232012712,
      "name": "__scsi_execute",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292842272,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292842272,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276748912,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276748912,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586341600,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586341600,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182928,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182928,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599088,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599088,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```

```json
{
  "name": "__scsi_execute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711360,
      "name": "__scsi_execute",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:248",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_sec_submit",
        "drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_do_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711360,
      "name": "__scsi_execute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int * resid)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u64 flags</code> ➡️ <code>blk_opf_t flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __scsi_execute(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, unsigned char * sense, struct scsi_sense_hdr * sshdr, int timeout, int retries, blk_opf_t flags, req_flags_t rq_flags, int * resid)
```
</details>
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
