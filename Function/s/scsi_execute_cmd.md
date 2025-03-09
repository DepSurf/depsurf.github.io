# Function: <code>scsi_execute_cmd</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int scsi_execute_cmd(struct scsi_device * sdev, const unsigned char * cmd, blk_opf_t opf, void * buffer, unsigned int bufflen, int timeout, int retries, const struct scsi_exec_args * args)
```

```json
{
  "name": "scsi_execute_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_execute_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:201",
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
        "drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug",
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
      "addr": 18446744071596787990,
      "name": "scsi_execute_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591242960,
      "name": "scsi_execute_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int scsi_execute_cmd(struct scsi_device * sdev, const unsigned char * cmd, blk_opf_t opf, void * buffer, unsigned int bufflen, int timeout, int retries, const struct scsi_exec_args * args)
```

```json
{
  "name": "scsi_execute_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_execute_cmd",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:201",
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
        "drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug",
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
      "addr": 18446744071597696966,
      "name": "scsi_execute_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591590208,
      "name": "scsi_execute_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int scsi_execute_cmd(struct scsi_device * sdev, const unsigned char * cmd, blk_opf_t opf, void * buffer, unsigned int bufflen, int timeout, int retries, const struct scsi_exec_args * args)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
