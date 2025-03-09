# Function: <code>scsi_get_cdrom_generic_arg</code>

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
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510336,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:660",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cdrom_send_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510336,
      "name": "scsi_get_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620560,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:651",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cdrom_send_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620560,
      "name": "scsi_get_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584650883,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:647",
      "file": "block/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/scsi_ioctl.c:scsi_cdrom_send_packet"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587950963,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:750",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589305467,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:733",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590869963,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:717",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591211200,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:720",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211200,
      "name": "scsi_get_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```

```json
{
  "name": "scsi_get_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591558384,
      "name": "scsi_get_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:720",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558384,
      "name": "scsi_get_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command * cgc, const void * arg)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
