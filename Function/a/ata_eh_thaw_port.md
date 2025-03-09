# Function: <code>ata_eh_thaw_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964000,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1266",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964000,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331200,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1266",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331200,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532240,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1266",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532240,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585630767,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1267",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615680,
      "name": "ata_eh_thaw_port.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585618304,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586062447,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1265",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047392,
      "name": "ata_eh_thaw_port.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586050032,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586309807,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1216",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295328,
      "name": "ata_eh_thaw_port.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586297840,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586451025,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1212",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436896,
      "name": "ata_eh_thaw_port.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586439360,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586685422,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681376,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586683952,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586842931,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828432,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586830992,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587636752,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1126",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636752,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587697696,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1126",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697696,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587576592,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1126",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576592,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158672,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1134",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158672,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589539072,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1131",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589539072,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591130144,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1130",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130144,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591488048,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1133",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488048,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591836640,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1142",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591836640,
      "name": "ata_eh_thaw_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499763156,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499757304,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336499760960,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232218292,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232202736,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 3232205860,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293108868,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293102272,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 13835058055293106272,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276929836,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276915674,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446743936276918304,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586601501,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587008,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586589568,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586470013,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455520,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586458080,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586797491,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782992,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586785552,
      "name": "ata_eh_thaw_port",
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
void ata_eh_thaw_port(struct ata_port * ap)
```

```json
{
  "name": "ata_eh_thaw_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586903587,
      "name": "ata_eh_thaw_port",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1195",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586889040,
      "name": "ata_eh_thaw_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586891600,
      "name": "ata_eh_thaw_port",
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
