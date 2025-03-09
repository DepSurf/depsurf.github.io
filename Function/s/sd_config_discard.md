# Function: <code>sd_config_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584850176,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:634",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850176,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212496,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:634",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212496,
      "name": "sd_config_discard",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407072,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:641",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407072,
      "name": "sd_config_discard",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491504,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:691",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491504,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585922624,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:699",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922624,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169824,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:699",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169824,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586312752,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:706",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586312752,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556192,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556192,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703408,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703408,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587520338,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:784",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504512,
      "name": "sd_config_discard",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587585999,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:817",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587571952,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587466623,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:817",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587453312,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588041695,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:817",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027744,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589404170,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:782",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390224,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590977770,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:782",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590963248,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591331322,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:784",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315632,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591680858,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:824",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591664416,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499613792,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499613792,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232069344,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232069344,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292928256,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292928256,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276798760,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276798760,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393888,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393888,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586270144,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270144,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586657968,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657968,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void sd_config_discard(struct scsi_disk * sdkp, unsigned int mode)
```

```json
{
  "name": "sd_config_discard",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586763920,
      "name": "sd_config_discard",
      "external": false,
      "loc": "drivers/scsi/sd.c:770",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763920,
      "name": "sd_config_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
