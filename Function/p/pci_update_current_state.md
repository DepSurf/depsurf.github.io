# Function: <code>pci_update_current_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261808,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:688",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261808,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583571888,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:709",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571888,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583708448,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:741",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708448,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583749376,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:736",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749376,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584008400,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:737",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008400,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584203952,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:749",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203952,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292256,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:920",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292256,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486432,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486432,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584622048,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622048,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304352,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:984",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304352,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585460592,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1124",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585460592,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340480,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1154",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340480,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797472,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1164",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797472,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586985057,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1099",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci.c:pci_refresh_power_state"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984720,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588151905,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1083",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci.c:pci_refresh_power_state"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151536,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588427457,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1097",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci.c:pci_refresh_power_state"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427088,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588723937,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1160",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci.c:pci_refresh_power_state"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723568,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496865648,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496865648,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230143668,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230143668,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290946240,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290946240,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275565722,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275565722,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584574208,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574208,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584502368,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502368,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584572208,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572208,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_update_current_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_update_current_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584679952,
      "name": "pci_update_current_state",
      "external": true,
      "loc": "drivers/pci/pci.c:931",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_platform_power_transition",
        "drivers/pci/pci.c:pci_refresh_power_state",
        "drivers/pci/pci-driver.c:pci_restore_standard_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679952,
      "name": "pci_update_current_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
