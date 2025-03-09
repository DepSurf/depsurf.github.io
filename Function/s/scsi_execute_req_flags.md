# Function: <code>scsi_execute_req_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_execute_req_flags(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, struct scsi_sense_hdr * sshdr, int timeout, int retries, int * resid, u64 flags)
```

```json
{
  "name": "scsi_execute_req_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804464,
      "name": "scsi_execute_req_flags",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:266",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_vpd_inquiry",
        "drivers/scsi/scsi.c:scsi_report_opcode",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_select",
        "drivers/scsi/scsi_lib.c:scsi_test_unit_ready",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_report_lun_scan",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804464,
      "name": "scsi_execute_req_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int scsi_execute_req_flags(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, struct scsi_sense_hdr * sshdr, int timeout, int retries, int * resid, u64 flags)
```

```json
{
  "name": "scsi_execute_req_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585165568,
      "name": "scsi_execute_req_flags",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:232",
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
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585165568,
      "name": "scsi_execute_req_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int scsi_execute_req_flags(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, struct scsi_sense_hdr * sshdr, int timeout, int retries, int * resid, u64 flags, req_flags_t rq_flags)
```

```json
{
  "name": "scsi_execute_req_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585359792,
      "name": "scsi_execute_req_flags",
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
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/sd.c:sd_start_stop_device",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:read_capacity_10",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_sync_cache",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359792,
      "name": "scsi_execute_req_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>req_flags_t rq_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int scsi_execute_req_flags(struct scsi_device * sdev, const unsigned char * cmd, int data_direction, void * buffer, unsigned int bufflen, struct scsi_sense_hdr * sshdr, int timeout, int retries, int * resid, u64 flags, req_flags_t rq_flags)
```
</details>
</li>
</ul>
