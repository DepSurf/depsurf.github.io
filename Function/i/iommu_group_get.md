# Function: <code>iommu_group_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584260480,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:551",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260480,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601532,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:542",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601408,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584783148,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:680",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783024,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584872556,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:724",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872432,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585291468,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:726",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291344,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585532901,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:727",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532784,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585657493,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:793",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585657376,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585882733,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:811",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585882288,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586025325,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024880,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586764141,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:969",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763680,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586943101,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:990",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942640,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586824845,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1019",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824384,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587385213,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1034",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384752,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588710997,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1038",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695488,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590178869,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1159",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590175040,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590501285,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1150",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590497552,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590851303,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1294",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590851120,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498825024,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498824520,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231431640,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/exynos-iommu.c:exynos_iommu_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231431208,
      "name": "iommu_group_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292036476,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_compound_attach",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292035712,
      "name": "iommu_group_get",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786301,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785856,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585645485,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645040,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585975341,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974896,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct iommu_group * iommu_group_get(struct device * dev)
```

```json
{
  "name": "iommu_group_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586083085,
      "name": "iommu_group_get",
      "external": true,
      "loc": "drivers/iommu/iommu.c:867",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082640,
      "name": "iommu_group_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_group * iommu_group_get(struct device * dev)
```
</details>
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
