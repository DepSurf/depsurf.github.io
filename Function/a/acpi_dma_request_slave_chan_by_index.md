# Function: <code>acpi_dma_request_slave_chan_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583818480,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:348",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818480,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145328,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145328,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325904,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325904,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405856,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405856,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584813727,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813232,
      "name": "acpi_dma_request_slave_chan_by_index.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071584813648,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585044159,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043664,
      "name": "acpi_dma_request_slave_chan_by_index.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071585044080,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151903,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:351",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151408,
      "name": "acpi_dma_request_slave_chan_by_index.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071585151824,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359267,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:348",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358768,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585359184,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585497795,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585497296,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585497712,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586221730,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:358",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221280,
      "name": "acpi_dma_request_slave_chan_by_index.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071586221888,
      "name": "acpi_dma_request_slave_chan_by_index",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586339408,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:358",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586339408,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214624,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:358",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214624,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720736,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:370",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720736,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587993264,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:370",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993264,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589359040,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:370",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359040,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657680,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:370",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657680,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968112,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:370",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968112,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498015796,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498015256,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446603336498015664,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585259875,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259376,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585259792,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585212499,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212000,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585212416,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448195,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447696,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585448112,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```

```json
{
  "name": "acpi_dma_request_slave_chan_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585556131,
      "name": "acpi_dma_request_slave_chan_by_index",
      "external": true,
      "loc": "drivers/dma/acpi-dma.c:356",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555632,
      "name": "acpi_dma_request_slave_chan_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585556048,
      "name": "acpi_dma_request_slave_chan_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct dma_chan * acpi_dma_request_slave_chan_by_index(struct device * dev, size_t index)
```
</details>
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
