# Function: <code>find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813883,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:263",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585826528,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:812",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait"
      ]
    },
    {
      "addr": 18446744071586149401,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:518",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_find_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826528,
      "name": "find_device",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207498,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:266",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220912,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:812",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071586565506,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:524",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220912,
      "name": "find_device",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586411962,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:266",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425408,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:812",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071586747058,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:515",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586425408,
      "name": "find_device",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586515674,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:268",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586530368,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:817",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071586874258,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:515",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530368,
      "name": "find_device",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586983082,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:268",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586997744,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:824",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071587359353,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:515",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586997744,
      "name": "find_device",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587280233,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:268",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298976,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:824",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071587665577,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:513",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298976,
      "name": "find_device",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587460457,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:267",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587479200,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:824",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071587796777,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:513",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479200,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587733881,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:267",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749696,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:824",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071588101897,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:514",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749696,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587938137,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587954480,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071588307593,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:514",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954480,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588792273,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588808149,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591127257,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:511",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588810219,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:224",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588826101,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591213817,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:596",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588696059,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:210",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588717365,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:926",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163001,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:596",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589384059,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:210",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589406677,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:931",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592014825,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:599",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588128635,
      "name": "find_device",
      "external": false,
      "loc": "drivers/xen/pci.c:269",
      "file": "drivers/xen/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_unregister_device_domain_owner",
        "drivers/xen/pci.c:xen_register_device_domain_owner",
        "drivers/xen/pci.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590860989,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:211",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590883291,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:938",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589517083,
      "name": "find_device",
      "external": false,
      "loc": "drivers/xen/pci.c:269",
      "file": "drivers/xen/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_unregister_device_domain_owner",
        "drivers/xen/pci.c:xen_register_device_domain_owner",
        "drivers/xen/pci.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592553453,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:210",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592572511,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:938",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589818043,
      "name": "find_device",
      "external": false,
      "loc": "drivers/xen/pci.c:269",
      "file": "drivers/xen/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_unregister_device_domain_owner",
        "drivers/xen/pci.c:xen_register_device_domain_owner",
        "drivers/xen/pci.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596967884,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:211",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593003247,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:963",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590154411,
      "name": "find_device",
      "external": false,
      "loc": "drivers/xen/pci.c:269",
      "file": "drivers/xen/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_unregister_device_domain_owner",
        "drivers/xen/pci.c:xen_register_device_domain_owner",
        "drivers/xen/pci.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597896094,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:217",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593754447,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:963",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501176600,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501194624,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501194624,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233682332,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3233700456,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233700456,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294687916,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294713136,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294713136,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277881092,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277895356,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277895356,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587569113,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587585456,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071587911241,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:514",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585456,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587337193,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587353536,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353536,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587894281,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587910624,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071588244649,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:514",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910624,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```

```json
{
  "name": "find_device",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588009545,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-table.c:265",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_get_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588025888,
      "name": "find_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:849",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry"
      ]
    },
    {
      "addr": 18446744071588377867,
      "name": "find_device",
      "external": false,
      "loc": "arch/x86/pci/xen.c:514",
      "file": "arch/x86/pci/xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_unregister_device_domain_owner",
        "arch/x86/pci/xen.c:xen_register_device_domain_owner",
        "arch/x86/pci/xen.c:xen_find_device_domain_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025888,
      "name": "find_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct dm_dev_internal * find_device(struct list_head * l, dev_t dev)
```
</details>
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
