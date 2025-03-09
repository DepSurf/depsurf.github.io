# Function: <code>__pci_enable_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool runtime, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258304,
      "name": "__pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:1845",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258304,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool runtime, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583567904,
      "name": "__pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:1866",
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
      "addr": 18446744071583567904,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool runtime, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583704800,
      "name": "__pci_enable_wake",
      "external": true,
      "loc": "drivers/pci/pci.c:1891",
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
      "addr": 18446744071583704800,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584198672,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:1978",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198672,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288128,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2151",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288128,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584483008,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2231",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483008,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618464,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618464,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585293408,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2297",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293408,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448304,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2441",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448304,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585328464,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2471",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328464,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585785470,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2502",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785424,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071592363536,
      "name": "__pci_enable_wake.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2564",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973296,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071594225599,
      "name": "__pci_enable_wake.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2538",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138640,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071596208141,
      "name": "__pci_enable_wake.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2576",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414016,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071596733319,
      "name": "__pci_enable_wake.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2689",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709328,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071597641740,
      "name": "__pci_enable_wake.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496859272,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496859272,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230139872,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230139872,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290941472,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290941472,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275561710,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275561710,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570624,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570624,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498784,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498784,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568624,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568624,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```

```json
{
  "name": "__pci_enable_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676608,
      "name": "__pci_enable_wake",
      "external": false,
      "loc": "drivers/pci/pci.c:2227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_enable_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676608,
      "name": "__pci_enable_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool runtime, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __pci_enable_wake(struct pci_dev * dev, pci_power_t state, bool enable)
```
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
