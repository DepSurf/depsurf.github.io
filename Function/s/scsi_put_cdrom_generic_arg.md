# Function: <code>scsi_put_cdrom_generic_arg</code>

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
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command * cgc, void * arg)
```

```json
{
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510144,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:690",
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
      "addr": 18446744071584510144,
      "name": "scsi_put_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command * cgc, void * arg)
```

```json
{
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620368,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:681",
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
      "addr": 18446744071584620368,
      "name": "scsi_put_cdrom_generic_arg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584651233,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "block/scsi_ioctl.c:677",
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
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587951313,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:780",
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
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589305914,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:763",
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
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590870380,
      "name": "scsi_put_cdrom_generic_arg",
      "external": false,
      "loc": "drivers/scsi/scsi_ioctl.c:747",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591213710,
      "name": "scsi_put_cdrom_generic_arg",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_put_cdrom_generic_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591560894,
      "name": "scsi_put_cdrom_generic_arg",
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
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command * cgc, void * arg)
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
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command * cgc, void * arg)
```
</details>
</li>
</ul>
