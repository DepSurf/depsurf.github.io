# Function: <code>pci_enable_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583258581,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1093",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_back_from_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274916,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1093",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583572726,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1087",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585876,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1087",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583709318,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1117",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723028,
      "name": "pci_enable_wake",
      "external": false,
      "loc": "include/linux/pci.h:1117",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745392,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:1911",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745392,
      "name": "pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003648,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:1914",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003648,
      "name": "pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198880,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2029",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198880,
      "name": "pci_enable_wake",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288352,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2205",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288352,
      "name": "pci_enable_wake",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584483232,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2285",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483232,
      "name": "pci_enable_wake",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618688,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618688,
      "name": "pci_enable_wake",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585308407,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2351",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293648,
      "name": "pci_enable_wake",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465146,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2495",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448544,
      "name": "pci_enable_wake",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585345272,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2525",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328704,
      "name": "pci_enable_wake",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585804391,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2563",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785680,
      "name": "pci_enable_wake",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586992710,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2625",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973488,
      "name": "pci_enable_wake",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588160228,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2599",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138848,
      "name": "pci_enable_wake",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588435748,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2637",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414224,
      "name": "pci_enable_wake",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588732582,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2750",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709536,
      "name": "pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496869780,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496859584,
      "name": "pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230147496,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230140172,
      "name": "pci_enable_wake",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290951744,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290941904,
      "name": "pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275569134,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275561958,
      "name": "pci_enable_wake",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584570848,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570848,
      "name": "pci_enable_wake",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584499008,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499008,
      "name": "pci_enable_wake",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584568848,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568848,
      "name": "pci_enable_wake",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pci_enable_wake(struct pci_dev * pci_dev, pci_power_t state, bool enable)
```

```json
{
  "name": "pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676832,
      "name": "pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676832,
      "name": "pci_enable_wake",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev * pci_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev * dev</code>
</li>
</ul>
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
