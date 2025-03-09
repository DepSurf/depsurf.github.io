# Function: <code>ata_dev_acpi_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010089,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011792,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585379184,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585379184,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580016,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580016,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663520,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663520,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586095744,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586095744,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586346149,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586343840,
      "name": "ata_dev_acpi_handle.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586344400,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586487429,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:59",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485088,
      "name": "ata_dev_acpi_handle.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586485680,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586732789,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730464,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586731040,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586879285,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876960,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586877536,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587688579,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587686720,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587749203,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747344,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587628254,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587626368,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588213406,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211520,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589598382,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596400,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591196446,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591194368,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591555758,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591553712,
      "name": "ata_dev_acpi_handle",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591904270,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591902128,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499815304,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499812168,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446603336499813392,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586637669,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635488,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586636064,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586506165,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503984,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586504560,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586833845,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831520,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586832096,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```

```json
{
  "name": "ata_dev_acpi_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586939957,
      "name": "ata_dev_acpi_handle",
      "external": true,
      "loc": "drivers/ata/libata-acpi.c:60",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF"
      ],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-zpodd.c:zpodd_exit",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937632,
      "name": "ata_dev_acpi_handle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586938208,
      "name": "ata_dev_acpi_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device * dev)
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
