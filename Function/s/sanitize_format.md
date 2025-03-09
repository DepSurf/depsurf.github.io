# Function: <code>sanitize_format</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585126000,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1561",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585126000,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585529555,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1561",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518912,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585717443,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1561",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706800,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585811874,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1559",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801200,
      "name": "sanitize_format.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586251018,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1559",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240208,
      "name": "sanitize_format.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586501624,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1556",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489648,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586649640,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1556",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637472,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586904568,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1557",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890976,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587101953,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088288,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587948479,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1567",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932816,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588009295,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1550",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993520,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587889567,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1550",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876096,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588497839,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1550",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483392,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589906543,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1551",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888160,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591483231,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1551",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465392,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591910367,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1534",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591886544,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592650207,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1534",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:cdrom_read_tocentry",
        "drivers/cdrom/cdrom.c:cdrom_multisession"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592626048,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500168656,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500157112,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232646532,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232634440,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293451668,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293432336,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277101822,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277088508,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586808033,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794368,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586749873,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736208,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587056513,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042848,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```

```json
{
  "name": "sanitize_format",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587163681,
      "name": "sanitize_format",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1564",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_get_last_written"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150016,
      "name": "sanitize_format",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void sanitize_format(union cdrom_addr * addr, u_char * curr, u_char requested)
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
