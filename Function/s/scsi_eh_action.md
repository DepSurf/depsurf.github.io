# Function: <code>scsi_eh_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584787160,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1106",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585147485,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1107",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585341773,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1107",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421712,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1094",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421712,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585851744,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1120",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851744,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098448,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1148",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098448,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586244544,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1145",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244544,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586488160,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1165",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488160,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586635968,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635968,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432064,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432064,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500784,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1176",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500784,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
enum scsi_disposition scsi_eh_action(struct scsi_cmnd * scmd, enum scsi_disposition rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382496,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1189",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382496,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587960365,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1208",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589316268,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1213",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590881388,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1220",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591224700,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1253",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591571868,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1256",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_stu",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices",
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499531768,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499531768,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231997000,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231997000,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292822608,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292822608,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276735516,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276735516,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586326448,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586326448,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167776,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167776,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586583936,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583936,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```

```json
{
  "name": "scsi_eh_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696160,
      "name": "scsi_eh_action",
      "external": false,
      "loc": "drivers/scsi/scsi_error.c:1168",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_test_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696160,
      "name": "scsi_eh_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int scsi_eh_action(struct scsi_cmnd * scmd, int rtn)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rtn</code> ➡️ <code>enum scsi_disposition rtn</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum scsi_disposition</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
enum scsi_disposition scsi_eh_action(struct scsi_cmnd * scmd, enum scsi_disposition rtn)
```
</details>
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
