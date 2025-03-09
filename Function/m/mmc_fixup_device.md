# Function: <code>mmc_fixup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975136,
      "name": "mmc_fixup_device",
      "external": true,
      "loc": "drivers/mmc/core/quirks.c:54",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975136,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380416,
      "name": "mmc_fixup_device",
      "external": true,
      "loc": "drivers/mmc/core/quirks.c:54",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_read_ext_csd",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380416,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589280,
      "name": "mmc_fixup_device",
      "external": true,
      "loc": "drivers/mmc/core/quirks.c:54",
      "file": "drivers/mmc/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589280,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586672983,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:123",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586699053,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:123",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587157351,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:138",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587183792,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:138",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587456674,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587484153,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587636882,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664260,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587915762,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587942446,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:141",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588121682,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588148341,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588985008,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071589012832,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985008,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071589012832,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588996192,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071589022208,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996192,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071589022208,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588883088,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071588908768,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588883088,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071588908768,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589586320,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071589615184,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589586320,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071589615184,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591082192,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:175",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071591113296,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:175",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591082192,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071591113296,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592799440,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:181",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071592834944,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:181",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592799440,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071592834944,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593235936,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:204",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071593271552,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:204",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593235936,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071593271552,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593990960,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:205",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ]
    },
    {
      "addr": 18446744071594027456,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:205",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593990960,
      "name": "mmc_fixup_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071594027456,
      "name": "mmc_fixup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501375884,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501401232,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501429812,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_probe"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233865180,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 3233890368,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 3233918188,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_probe"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294933256,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294966536,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277985862,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278008610,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278034800,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_probe"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587743250,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587769909,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588076210,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588102869,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
  "name": "mmc_fixup_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588193746,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_decode_ext_csd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588220405,
      "name": "mmc_fixup_device",
      "external": false,
      "loc": "drivers/mmc/core/quirks.h:148",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void mmc_fixup_device(struct mmc_card * card, const struct mmc_fixup * table)
```
</details>
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
