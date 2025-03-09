# Function: <code>spi_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585033790,
      "name": "spi_unregister_device",
      "external": false,
      "loc": "include/linux/spi/spi.h:1119",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417200,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:618",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417200,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618112,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:619",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618112,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585701824,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:635",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701824,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586137374,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:639",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137232,
      "name": "spi_unregister_device.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586137328,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586385786,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:643",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385648,
      "name": "spi_unregister_device.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586385744,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586527594,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:683",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527456,
      "name": "spi_unregister_device.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586527552,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586771349,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:689",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771216,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586771312,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586917722,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917584,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586917680,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587727130,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:702",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726992,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587727088,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587786634,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:711",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786496,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587786592,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587665898,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:712",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665712,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587665856,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588254458,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:771",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254272,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071588254416,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589635893,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:740",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635696,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071589635840,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591236869,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:802",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236640,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591236800,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591596405,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:803",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596176,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591596336,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592328117,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:842",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592327888,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071592328048,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499871728,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499871728,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232429064,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232429064,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293197536,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293197536,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276979708,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276979708,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586674746,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674608,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586674704,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586543082,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542944,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586543040,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872282,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872144,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586872240,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
```

```json
{
  "name": "spi_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978394,
      "name": "spi_unregister_device",
      "external": true,
      "loc": "drivers/spi/spi.c:690",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__unregister"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978256,
      "name": "spi_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586978352,
      "name": "spi_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void spi_unregister_device(struct spi_device * spi)
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
