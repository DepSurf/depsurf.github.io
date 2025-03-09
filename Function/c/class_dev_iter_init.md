# Function: <code>class_dev_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584402656,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:294",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_interface_unregister"
      ],
      "caller_func": [
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/extcon/extcon.c:extcon_register_interest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402656,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584738510,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:294",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738000,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584928398,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:309",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927888,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585013128,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:276",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012592,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585435384,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:276",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434848,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585678526,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:274",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678016,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585808766,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:274",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808272,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586042030,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041536,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586189662,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189168,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586952777,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:281",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950880,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587037753,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:281",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "block/blk-cgroup.c:blkcg_fill_root_iostats",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035872,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586921566,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:281",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "block/blk-cgroup.c:blkcg_print_stat",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919664,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587483966,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:281",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "block/blk-cgroup.c:blkcg_print_stat",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482064,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588805960,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:281",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "block/blk-cgroup.c:blkcg_print_stat",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588803728,
      "name": "class_dev_iter_init",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590303352,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:286",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "block/blk-cgroup.c:blkcg_fill_root_iostats",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300928,
      "name": "class_dev_iter_init",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void class_dev_iter_init(struct class_dev_iter * iter, const struct class * class, const struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590623719,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:310",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:disk_seqf_start",
        "block/early-lookup.c:printk_all_partitions",
        "block/early-lookup.c:blk_lookup_devt",
        "block/blk-cgroup.c:blkcg_fill_root_iostats",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590622176,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void class_dev_iter_init(struct class_dev_iter * iter, const struct class * class, const struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590982967,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:309",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device"
      ],
      "caller_func": [
        "block/genhd.c:disk_seqf_start",
        "block/early-lookup.c:printk_all_partitions",
        "block/early-lookup.c:blk_lookup_devt",
        "block/blk-cgroup.c:blkcg_fill_root_iostats",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981424,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498989468,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498988912,
      "name": "class_dev_iter_init",
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231557692,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231557164,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292142488,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292141712,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276364374,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276363946,
      "name": "class_dev_iter_init",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950030,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949536,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799086,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798592,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586139678,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586139184,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void class_dev_iter_init(struct class_dev_iter * iter, struct class * class, struct device * start, const struct device_type * type)
```

```json
{
  "name": "class_dev_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586248366,
      "name": "class_dev_iter_init",
      "external": true,
      "loc": "drivers/base/class.c:280",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_seqf_start",
        "block/genhd.c:printk_all_partitions",
        "drivers/phy/phy-core.c:of_phy_simple_xlate",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247872,
      "name": "class_dev_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device * start</code> ➡️ <code>const struct device * start</code>
</li>
</ul>
</details>
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
