# Function: <code>spi_alloc_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct spi_device * spi_alloc_device(struct spi_master * master)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585041376,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:438",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_new_device",
        "drivers/spi/spi.c:acpi_spi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041376,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct spi_device * spi_alloc_device(struct spi_master * master)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585427792,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:441",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427792,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct spi_device * spi_alloc_device(struct spi_master * master)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585628736,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:442",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628736,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712448,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:444",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712448,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586145008,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:448",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145008,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387696,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:452",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387696,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586529504,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:492",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586529504,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773136,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773136,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919504,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919504,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587734576,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:501",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734576,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587794576,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:510",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587794576,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587670112,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:506",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670112,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588260864,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:539",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260864,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589643088,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:509",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643088,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591252560,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:566",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252560,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591605536,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:567",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605536,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592337440,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:567",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592337440,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499864656,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:of_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499864656,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232428632,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:of_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232428632,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293204272,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:of_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293204272,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276985942,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:of_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276985942,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676528,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676528,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544864,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544864,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586874064,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874064,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct spi_device * spi_alloc_device(struct spi_controller * ctlr)
```

```json
{
  "name": "spi_alloc_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980192,
      "name": "spi_alloc_device",
      "external": true,
      "loc": "drivers/spi/spi.c:495",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:spi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980192,
      "name": "spi_alloc_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct spi_controller * ctlr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct spi_master * master</code>
</li>
</ul>
</details>
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
