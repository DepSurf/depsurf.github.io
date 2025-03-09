# Function: <code>pci_cfg_access_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230224,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:511",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230224,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538912,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:622",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538912,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675232,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:634",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675232,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715392,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:642",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715392,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972928,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:642",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972928,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167984,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_restore",
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167984,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255888,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255888,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584448912,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448912,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585632,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585632,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261520,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:269",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261520,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585419264,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:269",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419264,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585299808,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:269",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299808,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585756768,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:269",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585756768,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586940576,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:274",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940576,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098128,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:274",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098128,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588372560,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:274",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588372560,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588667328,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:274",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667328,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496818720,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496818720,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230104460,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230104460,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290894960,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290894960,
      "name": "pci_cfg_access_lock",
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275530834,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275530834,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537792,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537792,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465968,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465968,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535792,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535792,
      "name": "pci_cfg_access_lock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pci_cfg_access_lock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643376,
      "name": "pci_cfg_access_lock",
      "external": true,
      "loc": "drivers/pci/access.c:273",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_lock",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643376,
      "name": "pci_cfg_access_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
