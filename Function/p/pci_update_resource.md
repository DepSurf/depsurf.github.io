# Function: <code>pci_update_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290400,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:29",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290400,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601248,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:29",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601248,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738432,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:123",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738432,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780240,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:123",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780240,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584040848,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:124",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040848,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584237632,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237632,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584327360,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327360,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584522400,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523732,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584522352,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584657520,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658852,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584657472,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585341824,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:sriov_restore_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341824,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585494944,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:121",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:sriov_restore_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494944,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585374480,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:121",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585374480,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835296,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:121",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835296,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587027024,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:125",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027024,
      "name": "pci_update_resource",
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588205279,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:125",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204144,
      "name": "pci_update_resource",
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588480970,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:125",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479824,
      "name": "pci_update_resource",
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588778440,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:126",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ],
      "caller_func": [
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777200,
      "name": "pci_update_resource",
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496905664,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496905664,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230181716,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230181716,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290999152,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290999152,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275593922,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275593922,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584607984,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609316,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584607936,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584537808,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539140,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584537760,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584607680,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609012,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584607632,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void pci_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_update_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584715376,
      "name": "pci_update_resource",
      "external": true,
      "loc": "drivers/pci/setup-res.c:120",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/iov.c:pci_restore_iov_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716708,
      "name": "pci_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584715328,
      "name": "pci_update_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
