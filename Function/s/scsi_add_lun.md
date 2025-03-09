# Function: <code>scsi_add_lun</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584818266,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:765",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585179836,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:773",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585374628,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:771",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585459383,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:771",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585890135,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:772",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586137560,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:772",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586278401,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586519776,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519776,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667872,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667872,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466112,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:763",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466112,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587533824,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:763",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533824,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587416112,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:782",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587416112,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988976,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:788",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988976,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1461
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589346976,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:857",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346976,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590914704,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:857",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590914704,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591258000,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:859",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258000,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1553
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591605216,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:859",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605216,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1593
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499569696,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499569696,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232030072,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232030072,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292865776,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292865776,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1744
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276764098,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276764098,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586358352,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586358352,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586199664,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199664,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586615840,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586615840,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```

```json
{
  "name": "scsi_add_lun",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728336,
      "name": "scsi_add_lun",
      "external": false,
      "loc": "drivers/scsi/scsi_scan.c:764",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728336,
      "name": "scsi_add_lun",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int scsi_add_lun(struct scsi_device * sdev, unsigned char * inq_result, blist_flags_t * bflags, int async)
```
</details>
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
