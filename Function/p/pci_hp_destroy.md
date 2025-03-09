# Function: <code>pci_hp_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584406866,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406800,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602994,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602928,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584740818,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740752,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585431298,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430688,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585583234,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582624,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585462738,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461184,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585928994,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926880,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587131218,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128944,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588331282,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328704,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588607378,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588604800,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907458,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904880,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497003312,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497003224,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291077224,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291077104,
      "name": "pci_hp_destroy",
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275666164,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275666082,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689634,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689568,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584620402,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620336,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584690978,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690912,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pci_hp_destroy(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584798626,
      "name": "pci_hp_destroy",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:551",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_remove",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798560,
      "name": "pci_hp_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void pci_hp_destroy(struct hotplug_slot * slot)
```
</details>
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
void pci_hp_destroy(struct hotplug_slot * slot)
```
</details>
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
