# Function: <code>sd_zbc_check_zoned_characteristics</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586338820,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:265",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586582116,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:290",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586729508,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587530912,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:544",
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
      "addr": 18446744071587530912,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587597904,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:545",
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
      "addr": 18446744071587597904,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587482122,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:548",
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
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588057978,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:547",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:630",
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
      "addr": 18446744071589417952,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071594401397,
      "name": "sd_zbc_check_zoned_characteristics.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:636",
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
      "addr": 18446744071590994704,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071596261457,
      "name": "sd_zbc_check_zoned_characteristics.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:638",
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
      "addr": 18446744071591347744,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071596789573,
      "name": "sd_zbc_check_zoned_characteristics.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:638",
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
      "addr": 18446744071591697632,
      "name": "sd_zbc_check_zoned_characteristics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071597698653,
      "name": "sd_zbc_check_zoned_characteristics.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499640912,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232095756,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292962688,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276824258,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586419988,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586296244,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586684068,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_check_zoned_characteristics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586790100,
      "name": "sd_zbc_check_zoned_characteristics",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:286",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
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
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int sd_zbc_check_zoned_characteristics(struct scsi_disk * sdkp, unsigned char * buf)
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
