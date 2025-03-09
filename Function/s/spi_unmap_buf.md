# Function: <code>spi_unmap_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585034512,
      "name": "spi_unmap_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:743",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034512,
      "name": "spi_unmap_buf.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585421888,
      "name": "spi_unmap_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:768",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421888,
      "name": "spi_unmap_buf.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585622080,
      "name": "spi_unmap_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:787",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622080,
      "name": "spi_unmap_buf.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "spi_unmap_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705792,
      "name": "spi_unmap_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:814",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705792,
      "name": "spi_unmap_buf.isra.32",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586138288,
      "name": "spi_unmap_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:818",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138288,
      "name": "spi_unmap_buf.isra.31",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392432,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:828",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392432,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534272,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:870",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534272,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586780288,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:887",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780288,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926720,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926720,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587740784,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:914",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_map_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740784,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587803257,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:932",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805744,
      "name": "spi_unmap_buf",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587682793,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:944",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685264,
      "name": "spi_unmap_buf",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588272664,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1004",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275248,
      "name": "spi_unmap_buf",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589654664,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1044",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657600,
      "name": "spi_unmap_buf",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591267440,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267440,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591622240,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591622240,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592355104,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1192",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592355104,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499890032,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499890032,
      "name": "spi_unmap_buf",
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232441276,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232441276,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293215072,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293215072,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276990934,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276990934,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683744,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683744,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552080,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552080,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881280,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881280,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
```

```json
{
  "name": "spi_unmap_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586987408,
      "name": "spi_unmap_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:888",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586987408,
      "name": "spi_unmap_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void spi_unmap_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, enum dma_data_direction dir)
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
