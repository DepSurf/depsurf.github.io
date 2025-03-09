# Function: <code>scsi_cdrom_send_packet</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512192,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "block/scsi_ioctl.c:719",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512192,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
int scsi_cdrom_send_packet(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584622112,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "block/scsi_ioctl.c:710",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622112,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
int scsi_cdrom_send_packet(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584650832,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "block/scsi_ioctl.c:706",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650832,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int scsi_cdrom_send_packet(struct scsi_device * sdev, struct gendisk * disk, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587950912,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:809",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950912,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int scsi_cdrom_send_packet(struct scsi_device * sdev, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589305376,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:792",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589305376,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
int scsi_cdrom_send_packet(struct scsi_device * sdev, fmode_t mode, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590869872,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:776",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590869872,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int scsi_cdrom_send_packet(struct scsi_device * sdev, bool open_for_write, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591213312,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:779",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213312,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
int scsi_cdrom_send_packet(struct scsi_device * sdev, bool open_for_write, void * arg)
```

```json
{
  "name": "scsi_cdrom_send_packet",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591560496,
      "name": "scsi_cdrom_send_packet",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:779",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591560496,
      "name": "scsi_cdrom_send_packet",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int scsi_cdrom_send_packet(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, void * arg)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_device * sdev</code>
</li>
<li>
<b>Param added. </b>
<code>struct gendisk * disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gendisk * bd_disk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk * disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, disk, mode, arg</code> ➡️ <code>sdev, mode, arg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
