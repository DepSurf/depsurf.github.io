# Function: <code>spi_map_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585036144,
      "name": "spi_map_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:683",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036144,
      "name": "spi_map_buf.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
  "name": "spi_map_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585421120,
      "name": "spi_map_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:706",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421120,
      "name": "spi_map_buf.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
  "name": "spi_map_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585623776,
      "name": "spi_map_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:712",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623776,
      "name": "spi_map_buf.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
  "name": "spi_map_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585707504,
      "name": "spi_map_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:739",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707504,
      "name": "spi_map_buf.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
  "name": "spi_map_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586140032,
      "name": "spi_map_buf",
      "external": false,
      "loc": "drivers/spi/spi.c:743",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140032,
      "name": "spi_map_buf.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391760,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:747",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391760,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586533568,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:789",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586533568,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586779584,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:806",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586779584,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926000,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926000,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587740096,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:833",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740096,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587802016,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:851",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587802016,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587681584,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:863",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587681584,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271376,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:923",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271376,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653328,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:963",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653328,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591267376,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267376,
      "name": "spi_map_buf",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591622176,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591622176,
      "name": "spi_map_buf",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592355040,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:1172",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592355040,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499889328,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499889328,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232440448,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232440448,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293213824,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293213824,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276990306,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276990306,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683024,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683024,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551360,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551360,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586880560,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880560,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
```

```json
{
  "name": "spi_map_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586986688,
      "name": "spi_map_buf",
      "external": true,
      "loc": "drivers/spi/spi.c:807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986688,
      "name": "spi_map_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int spi_map_buf(struct spi_controller * ctlr, struct device * dev, struct sg_table * sgt, void * buf, size_t len, enum dma_data_direction dir)
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
