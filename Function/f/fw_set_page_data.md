# Function: <code>fw_set_page_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475008,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_class.c:387",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475008,
      "name": "fw_set_page_data.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fw_set_page_data(struct firmware_buf * buf, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584820512,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_class.c:383",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584820512,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fw_set_page_data(struct firmware_buf * buf, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585014064,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_class.c:451",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014064,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585102893,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_class.c:447",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099440,
      "name": "fw_set_page_data.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585528781,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_class.c:451",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525216,
      "name": "fw_set_page_data.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585766352,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:355",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766352,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899552,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:361",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899552,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586137856,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137856,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586286336,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286336,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055408,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:553",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055408,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587139824,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:588",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139824,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027136,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:590",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027136,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587594416,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:591",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594416,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588931472,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:594",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931472,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590445360,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:594",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590445360,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590765040,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:603",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590765040,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591107328,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:604",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591107328,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499117560,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499117560,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231666436,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231666436,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292302432,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292302432,
      "name": "fw_set_page_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276436268,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276436268,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586049584,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049584,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585895536,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585895536,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236352,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236352,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```

```json
{
  "name": "fw_set_page_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345328,
      "name": "fw_set_page_data",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345328,
      "name": "fw_set_page_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void fw_set_page_data(struct firmware_buf * buf, struct firmware * fw)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void fw_set_page_data(struct firmware_buf * buf, struct firmware * fw)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void fw_set_page_data(struct fw_priv * fw_priv, struct firmware * fw)
```
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
