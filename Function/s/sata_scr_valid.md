# Function: <code>sata_scr_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584904800,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5115",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904800,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585271906,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5307",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267392,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585471458,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5349",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466944,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585555010,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5435",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550912,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585986706,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5466",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982608,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586235074,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5482",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230960,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586375490,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5486",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371376,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586619186,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5471",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586615072,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586766738,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762512,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587662064,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656416,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587723008,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717360,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587602144,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596560,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588186576,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180784,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589569091,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589562912,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591163395,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:39",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591156176,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591522547,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:41",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591514656,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591870963,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:41",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd",
        "drivers/ata/libata-sata.c:sata_scr_write_flush",
        "drivers/ata/libata-sata.c:sata_scr_write"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591863328,
      "name": "sata_scr_valid",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499687244,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499683216,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232134544,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232129568,
      "name": "sata_scr_valid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293017376,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293010048,
      "name": "sata_scr_valid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276857782,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276853982,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525474,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521248,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586394050,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389824,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586721298,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717072,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int sata_scr_valid(struct ata_link * link)
```

```json
{
  "name": "sata_scr_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586827474,
      "name": "sata_scr_valid",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5495",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:sata_scr_write_flush",
        "drivers/ata/libata-core.c:sata_scr_write",
        "drivers/ata/libata-core.c:sata_scr_read",
        "drivers/ata/libata-core.c:ata_dev_configure"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_std_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823040,
      "name": "sata_scr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
