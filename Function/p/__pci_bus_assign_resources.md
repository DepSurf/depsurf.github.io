# Function: <code>__pci_bus_assign_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302592,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1385",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302592,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613584,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1389",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613584,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750784,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1390",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750784,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792672,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1381",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792672,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055152,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1381",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055152,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254688,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1376",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254688,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344448,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1378",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344448,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541403,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584538112,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676526,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584673248,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1378",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363431,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585360064,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1379",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591397968,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585511808,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1379",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340202,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585390272,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1379",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592367916,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585851904,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1379",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594230268,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587044976,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225792,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1379",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225792,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588501264,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1372",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501264,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588799664,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1382",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588799664,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496922816,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496922816,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230198628,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230198628,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291021088,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291021088,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275608260,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275608260,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626994,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584623712,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556814,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584553536,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626686,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584623408,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void __pci_bus_assign_resources(const struct pci_bus * bus, struct list_head * realloc_head, struct list_head * fail_head)
```

```json
{
  "name": "__pci_bus_assign_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_bus_assign_resources",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:1341",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734382,
      "name": "__pci_bus_assign_resources.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584731104,
      "name": "__pci_bus_assign_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
