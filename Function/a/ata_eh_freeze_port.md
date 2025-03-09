# Function: <code>ata_eh_freeze_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584963920,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1245",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963920,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331120,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1245",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331120,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532160,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1245",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532160,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585624980,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1246",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615616,
      "name": "ata_eh_freeze_port.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585618272,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586056651,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1244",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047328,
      "name": "ata_eh_freeze_port.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586050000,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586304623,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295264,
      "name": "ata_eh_freeze_port.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586297808,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586446159,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1191",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436832,
      "name": "ata_eh_freeze_port.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586439328,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586691455,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681312,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586683920,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586837743,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828368,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586830960,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587633481,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1104",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587631200,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587694427,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1104",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692160,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587573627,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1104",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587571344,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588155088,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1112",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155088,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589535840,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1109",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534432,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591126384,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1108",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591125232,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591483680,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1111",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482528,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591832452,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1123",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591830768,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499769172,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499757144,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446603336499760904,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232213064,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232202676,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3232205816,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293116644,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293102160,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 13835058055293106224,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276925054,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276915604,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446743936276918256,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596319,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586944,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586589536,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586464831,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455456,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586458048,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586792303,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782928,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586785520,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ata_eh_freeze_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_freeze_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898399,
      "name": "ata_eh_freeze_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1174",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888976,
      "name": "ata_eh_freeze_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586891568,
      "name": "ata_eh_freeze_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
