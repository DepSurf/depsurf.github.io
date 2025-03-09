# Function: <code>spi_get_gpio_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586774533,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2282",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586920473,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2469",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587725312,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071587745974,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2545",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587784976,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071591529241,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2565",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664512,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071591471377,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2699",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252560,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071592540088,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2807",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634000,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071594419399,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2990",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591233424,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
    },
    {
      "addr": 18446744071596265254,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2997",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591593152,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071596793393,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:3150",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324112,
      "name": "spi_get_gpio_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071597716366,
      "name": "spi_get_gpio_descs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499886188,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232434160,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293207192,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276987892,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586677497,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586545833,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586875033,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_get_gpio_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586981161,
      "name": "spi_get_gpio_descs",
      "external": false,
      "loc": "drivers/spi/spi.c:2288",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int spi_get_gpio_descs(struct spi_controller * ctlr)
```
</details>
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
