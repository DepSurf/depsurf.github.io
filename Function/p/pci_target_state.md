# Function: <code>pci_target_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pci_power_t pci_target_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249648,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1919",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_dev_keep_suspended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249648,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
pci_power_t pci_target_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583559008,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1940",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559008,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
pci_power_t pci_target_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695872,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1965",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695872,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583742864,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1978",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742864,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584001104,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1988",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001104,
      "name": "pci_target_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584195056,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2069",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195056,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584284512,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2245",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284512,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584479040,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2325",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479040,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584614528,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614528,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585284896,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2391",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284896,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439456,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2535",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439456,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319568,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2565",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319568,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777152,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2603",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777152,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974368,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2665",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974368,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588139872,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2639",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139872,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588415728,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2677",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415728,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588711040,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2790",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711040,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496854336,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496854336,
      "name": "pci_target_state",
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230135448,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230135448,
      "name": "pci_target_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290934800,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290934800,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275557368,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275557368,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584566688,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566688,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584494848,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494848,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584564688,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564688,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
pci_power_t pci_target_state(struct pci_dev * dev, bool wakeup)
```

```json
{
  "name": "pci_target_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584672672,
      "name": "pci_target_state",
      "external": false,
      "loc": "drivers/pci/pci.c:2321",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_dev_run_wake",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672672,
      "name": "pci_target_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
<code>bool wakeup</code>
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
