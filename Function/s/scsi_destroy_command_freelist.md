# Function: <code>scsi_destroy_command_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_destroy_command_freelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774416,
      "name": "scsi_destroy_command_freelist",
      "external": true,
      "loc": "drivers/scsi/scsi.c:454",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_host_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774416,
      "name": "scsi_destroy_command_freelist",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_destroy_command_freelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585134336,
      "name": "scsi_destroy_command_freelist",
      "external": true,
      "loc": "drivers/scsi/scsi.c:454",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134336,
      "name": "scsi_destroy_command_freelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void scsi_destroy_command_freelist(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_destroy_command_freelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328480,
      "name": "scsi_destroy_command_freelist",
      "external": true,
      "loc": "drivers/scsi/scsi.c:454",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328480,
      "name": "scsi_destroy_command_freelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host * shost)
```
</details>
</li>
</ul>
