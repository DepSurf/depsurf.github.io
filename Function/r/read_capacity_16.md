# Function: <code>read_capacity_16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863664,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2048",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863664,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585226592,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2059",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585226592,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422672,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2112",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422672,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585510476,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2262",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507664,
      "name": "read_capacity_16.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585942214,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2300",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938208,
      "name": "read_capacity_16.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586189247,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184320,
      "name": "read_capacity_16.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586332221,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2258",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586326256,
      "name": "read_capacity_16.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586569201,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2261",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567584,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586716351,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714736,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587526384,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2291",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525040,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587590400,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2335",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587589056,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587470960,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2350",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587469632,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588046064,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2313",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044736,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407264,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2253",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407264,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1065
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590981040,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2294",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981040,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591334592,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2402",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591334592,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591684128,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2453",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591684128,
      "name": "read_capacity_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499627836,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499626568,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232081808,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232080508,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292945632,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292943728,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276809904,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276808516,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586406831,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405216,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586283087,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281472,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586670911,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669296,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_capacity_16",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776863,
      "name": "read_capacity_16",
      "external": false,
      "loc": "drivers/scsi/sd.c:2271",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sd.c:sd_read_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586775248,
      "name": "read_capacity_16.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int read_capacity_16(struct scsi_disk * sdkp, struct scsi_device * sdp, unsigned char * buffer)
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
