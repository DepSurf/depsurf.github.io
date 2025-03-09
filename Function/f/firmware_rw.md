# Function: <code>firmware_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf * buf, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584819136,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_class.c:724",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/base/firmware_class.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819136,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
void firmware_rw(struct firmware_buf * buf, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012704,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_class.c:785",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/base/firmware_class.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012704,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf * buf, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097824,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_class.c:815",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/base/firmware_class.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097824,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void firmware_rw(struct firmware_buf * buf, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523648,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_class.c:819",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/base/firmware_class.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523648,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771920,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:338",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771920,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905168,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:333",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905168,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144704,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144704,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293184,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293184,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063264,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:316",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063264,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147792,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:316",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147792,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587035024,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:314",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035024,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587602160,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:314",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587602160,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588942336,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/sysfs.c:241",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/sysfs.c:firmware_data_write",
        "drivers/base/firmware_loader/sysfs.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942336,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590457344,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/sysfs.c:240",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/sysfs.c:firmware_data_write",
        "drivers/base/firmware_loader/sysfs.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590457344,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590777616,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/sysfs.c:240",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/sysfs.c:firmware_data_write",
        "drivers/base/firmware_loader/sysfs.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590777616,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591120288,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/sysfs.c:240",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/sysfs.c:firmware_data_write",
        "drivers/base/firmware_loader/sysfs.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120288,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499126608,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499126608,
      "name": "firmware_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231674620,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292315296,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292315296,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276440768,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276440768,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586056432,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056432,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902384,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902384,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586242496,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586242496,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```

```json
{
  "name": "firmware_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586352176,
      "name": "firmware_rw",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:313",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586352176,
      "name": "firmware_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void firmware_rw(struct firmware_buf * buf, char * buffer, loff_t offset, size_t count, bool read)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fw_priv * fw_priv</code>
</li>
<li>
<b>Param removed. </b>
<code>struct firmware_buf * buf</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void firmware_rw(struct fw_priv * fw_priv, char * buffer, loff_t offset, size_t count, bool read)
```
</details>
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
