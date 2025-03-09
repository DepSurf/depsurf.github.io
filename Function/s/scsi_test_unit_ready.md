# Function: <code>scsi_test_unit_ready</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr_external)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806256,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2529",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806256,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr_external)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167328,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2402",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167328,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr_external)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585361584,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2443",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361584,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437488,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2523",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437488,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868112,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2601",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868112,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586114240,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2617",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114240,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260576,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260576,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586504656,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2161",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586504656,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652544,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652544,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587448496,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2189",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl_common",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587448496,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516560,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2197",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl_common",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516560,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398176,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2214",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl_common",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398176,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587969888,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2207",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969888,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333392,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2273",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333392,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590899760,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2278",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590899760,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591243728,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2291",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591243728,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591590976,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2288",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591590976,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499550552,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499550552,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232014032,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232014032,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292843952,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292843952,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276750024,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276750024,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586343024,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586343024,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184352,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/storvsc_drv.c:storvsc_host_scan",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184352,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600512,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600512,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int scsi_test_unit_ready(struct scsi_device * sdev, int timeout, int retries, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_test_unit_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586712784,
      "name": "scsi_test_unit_ready",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2208",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sd.c:sd_check_events",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr_ioctl.c:sr_drive_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712784,
      "name": "scsi_test_unit_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_sense_hdr * sshdr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct scsi_sense_hdr * sshdr_external</code>
</li>
</ul>
</details>
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
