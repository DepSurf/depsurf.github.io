# Function: <code>spi_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585039376,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:2426",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/base/regmap/regmap-spi.c:spi_write",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_write",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_read",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585039376,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585426640,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:2896",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/base/regmap/regmap-spi.c:spi_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426640,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585627584,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:2923",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585627584,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585711264,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3086",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585711264,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586143824,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3156",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143824,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396400,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3156",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396400,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586538336,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3255",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538336,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586784272,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3484",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586784272,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586930656,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930656,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587745703,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3778",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745296,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587805527,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3874",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805120,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587685058,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3921",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684640,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588275042,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3979",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274624,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589657375,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3979",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656896,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591261496,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:4240",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260976,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591616351,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:4295",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615840,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592348079,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:4462",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_write_then_read"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592347568,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499894776,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499894776,
      "name": "spi_sync",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232445580,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_batch_read",
        "drivers/tty/serial/max310x.c:max310x_batch_write",
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232445580,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293220512,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293220512,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276994628,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276994628,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687680,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687680,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556016,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556016,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885216,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885216,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int spi_sync(struct spi_device * spi, struct spi_message * message)
```

```json
{
  "name": "spi_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991600,
      "name": "spi_sync",
      "external": true,
      "loc": "drivers/spi/spi.c:3488",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_putget",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991600,
      "name": "spi_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
