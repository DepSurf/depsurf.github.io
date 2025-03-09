# Function: <code>scsi_get_vpd_size</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_get_vpd_size(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589297728,
      "name": "scsi_get_vpd_size",
      "external": false,
      "loc": "drivers/scsi/scsi.c:324",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_get_vpd_buf",
        "drivers/scsi/scsi.c:scsi_get_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297728,
      "name": "scsi_get_vpd_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int scsi_get_vpd_size(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590860624,
      "name": "scsi_get_vpd_size",
      "external": false,
      "loc": "drivers/scsi/scsi.c:324",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_get_vpd_buf",
        "drivers/scsi/scsi.c:scsi_get_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590860624,
      "name": "scsi_get_vpd_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int scsi_get_vpd_size(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591202944,
      "name": "scsi_get_vpd_size",
      "external": false,
      "loc": "drivers/scsi/scsi.c:331",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_get_vpd_buf",
        "drivers/scsi/scsi.c:scsi_get_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202944,
      "name": "scsi_get_vpd_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int scsi_get_vpd_size(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_get_vpd_size",
      "external": false,
      "loc": "drivers/scsi/scsi.c:336",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_get_vpd_buf",
        "drivers/scsi/scsi.c:scsi_get_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547952,
      "name": "scsi_get_vpd_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071597696739,
      "name": "scsi_get_vpd_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int scsi_get_vpd_size(struct scsi_device * sdev, u8 page)
```
</details>
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
