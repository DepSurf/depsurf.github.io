# Function: <code>scsi_get_vpd_buf</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841840,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:421",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841840,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586088928,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:421",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586088928,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235104,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:421",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235104,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586478608,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586478608,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626400,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626400,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587421744,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:387",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421744,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587491440,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:387",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491440,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373184,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:400",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373184,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940800,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:393",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940800,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:400",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589298144,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071594396948,
      "name": "scsi_get_vpd_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:400",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590861136,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071596259827,
      "name": "scsi_get_vpd_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:410",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203456,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071596787850,
      "name": "scsi_get_vpd_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:428",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591548592,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071597696793,
      "name": "scsi_get_vpd_buf.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499518216,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499518216,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231987076,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231987076,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292808832,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292808832,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276726738,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276726738,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586316880,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586316880,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158208,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158208,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574368,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574368,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```

```json
{
  "name": "scsi_get_vpd_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686592,
      "name": "scsi_get_vpd_buf",
      "external": false,
      "loc": "drivers/scsi/scsi.c:401",
      "file": "drivers/scsi/scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_update_vpd_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686592,
      "name": "scsi_get_vpd_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct scsi_vpd * scsi_get_vpd_buf(struct scsi_device * sdev, u8 page)
```
</details>
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
