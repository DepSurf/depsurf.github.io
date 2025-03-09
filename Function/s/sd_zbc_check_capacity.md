# Function: <code>sd_zbc_check_capacity</code>

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
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585434463,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:407",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585518734,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:395",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585950452,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:450",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586197227,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:357",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
int sd_zbc_check_capacity(struct scsi_disk * sdkp, unsigned char * buf, u32 * zblocks)
```

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587530560,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:595",
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
      "addr": 18446744071587530560,
      "name": "sd_zbc_check_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int sd_zbc_check_capacity(struct scsi_disk * sdkp, unsigned char * buf, u32 * zblocks)
```

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587597360,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:596",
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
      "addr": 18446744071587597360,
      "name": "sd_zbc_check_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587482223,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:599",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588058079,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:598",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
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
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:706",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417440,
      "name": "sd_zbc_check_capacity.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071594401354,
      "name": "sd_zbc_check_capacity.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:712",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590993504,
      "name": "sd_zbc_check_capacity.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071596261311,
      "name": "sd_zbc_check_capacity.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:714",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347232,
      "name": "sd_zbc_check_capacity.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596789536,
      "name": "sd_zbc_check_capacity.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_capacity",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:714",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697120,
      "name": "sd_zbc_check_capacity.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071597698616,
      "name": "sd_zbc_check_capacity.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int sd_zbc_check_capacity(struct scsi_disk * sdkp, unsigned char * buf, u32 * zblocks)
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
int sd_zbc_check_capacity(struct scsi_disk * sdkp, unsigned char * buf, u32 * zblocks)
```
</details>
</li>
</ul>
