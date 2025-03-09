# Function: <code>pci_cfg_access_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583228144,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:553",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228144,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583536832,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:664",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536832,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673168,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:676",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673168,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713232,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:684",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:__pci_reset_function",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713232,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970720,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:684",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970720,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166336,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_restore",
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166336,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254128,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_restore",
        "drivers/pci/pci.c:pci_bus_save_and_disable",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254128,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450142,
      "name": "pci_cfg_access_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584447232,
      "name": "pci_cfg_access_unlock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583984,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583984,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259840,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:311",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259840,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417568,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:311",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417568,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298128,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:311",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298128,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755088,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:311",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755088,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586940672,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:316",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940672,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098240,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:316",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098240,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588372672,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:316",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588372672,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588667440,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:316",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667440,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496822496,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496822496,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230104576,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230104576,
      "name": "pci_cfg_access_unlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290891280,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290891280,
      "name": "pci_cfg_access_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275529218,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275529218,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536144,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536144,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464320,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464320,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534144,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534144,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_cfg_access_unlock(struct pci_dev * dev)
```

```json
{
  "name": "pci_cfg_access_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643456,
      "name": "pci_cfg_access_unlock",
      "external": true,
      "loc": "drivers/pci/access.c:315",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_unlock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_bus_unlock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/pci/pci.c:pci_reset_function",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643456,
      "name": "pci_cfg_access_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
