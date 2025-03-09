# Function: <code>twl_i2c_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643120,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:482",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643120,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991376,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:482",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991376,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174880,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:481",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174880,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585256768,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:481",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256768,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684864,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:481",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684864,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:481",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932373,
      "name": "twl_i2c_read.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585930848,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:481",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070606,
      "name": "twl_i2c_read.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586067104,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305619,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586302272,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453798,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586450448,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl-core.c:twl_read_idcode_register",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230774,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587226592,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl-core.c:twl_read_idcode_register",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591505985,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587297296,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448984,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587184704,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592510689,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587746672,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594379639,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589091296,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590627120,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590627120,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590968144,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:471",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590968144,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591311984,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:473",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311984,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499315736,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499315736,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231863872,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-twl4030.c:twl_get_direction",
        "drivers/gpio/gpio-twl4030.c:twl_get",
        "drivers/gpio/gpio-twl4030.c:twl_request",
        "drivers/gpio/gpio-twl4030.c:twl4030_set_gpio_direction",
        "drivers/regulator/twl-regulator.c:twl4030smps_get_voltage",
        "drivers/regulator/twl-regulator.c:twl4030ldo_get_voltage_sel",
        "drivers/regulator/twl-regulator.c:twl4030reg_set_mode",
        "drivers/regulator/twl-regulator.c:twl4030_wait_pb_ready",
        "drivers/regulator/twl-regulator.c:twlreg_grp",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twlreg_probe",
        "drivers/regulator/twl6030-regulator.c:twl6030smps_get_voltage_sel",
        "drivers/regulator/twl6030-regulator.c:twl6030ldo_get_voltage_sel",
        "drivers/regulator/twl6030-regulator.c:twl6030reg_get_status",
        "drivers/regulator/twl6030-regulator.c:twl6030reg_is_enabled",
        "drivers/regulator/twl6030-regulator.c:twlreg_grp",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/twl4030-power.c:twl4030_power_probe",
        "drivers/mfd/twl4030-power.c:twl4030_power_probe",
        "drivers/mfd/twl4030-power.c:twl4030_power_probe",
        "drivers/mfd/twl4030-power.c:twl4030_power_probe",
        "drivers/mfd/twl4030-power.c:twl4030_power_off",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-power.c:twl4030_power_configure_scripts",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource",
        "drivers/rtc/rtc-twl.c:twl_rtc_interrupt",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231863872,
      "name": "twl_i2c_read",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292534448,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292534448,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276564158,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276564158,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401766,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586398416,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```

```json
{
  "name": "twl_i2c_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "twl_i2c_read",
      "external": true,
      "loc": "drivers/mfd/twl-core.c:468",
      "file": "drivers/mfd/twl-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_get_hfclk_rate",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_mask",
        "drivers/mfd/twl6030-irq.c:twl6030_interrupt_unmask",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_disable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_enable_resource",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513446,
      "name": "twl_i2c_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586510096,
      "name": "twl_i2c_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int twl_i2c_read(u8 mod_no, u8 * value, u8 reg, unsigned int num_bytes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
