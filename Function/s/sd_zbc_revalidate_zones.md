# Function: <code>sd_zbc_revalidate_zones</code>

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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp, u32 zone_blocks, unsigned int nr_zones)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532192,
      "name": "sd_zbc_revalidate_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:682",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532192,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587600560,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:683",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600560,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481072,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:702",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481072,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:701",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592530500,
      "name": "sd_zbc_revalidate_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588056912,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:820",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594402174,
      "name": "sd_zbc_revalidate_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589422288,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 841
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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:826",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262123,
      "name": "sd_zbc_revalidate_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590998752,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:828",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596790319,
      "name": "sd_zbc_revalidate_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071591352480,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_zbc_revalidate_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_revalidate_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:828",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597699658,
      "name": "sd_zbc_revalidate_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071591702416,
      "name": "sd_zbc_revalidate_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int sd_zbc_revalidate_zones(struct scsi_disk * sdkp, u32 zone_blocks, unsigned int nr_zones)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 zone_blocks</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_zones</code>
</li>
</ul>
</details>
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
