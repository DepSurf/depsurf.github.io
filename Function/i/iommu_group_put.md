# Function: <code>iommu_group_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584260288,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:569",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260288,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584608075,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:560",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600880,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584791003,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:711",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782448,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584880299,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:755",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871600,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585300075,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:757",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290928,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585540798,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:758",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532560,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585665182,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:824",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_request_dm_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656688,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585882792,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:842",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881584,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586025384,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024176,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586764200,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1001",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
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
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763216,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586943160,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1022",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
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
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941840,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586824904,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1051",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
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
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823584,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587385272,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1066",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
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
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384112,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588711064,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1070",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_noiommu_group_alloc",
        "drivers/vfio/vfio.c:vfio_noiommu_group_alloc",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698752,
      "name": "iommu_group_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590178965,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1191",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178704,
      "name": "iommu_group_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590501381,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1182",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590501120,
      "name": "iommu_group_put",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590862832,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1326",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:__iommu_group_remove_device",
        "drivers/iommu/iommu.c:__iommu_group_remove_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/iommu/iommu.c:iommu_device_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590854864,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498825076,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/arm-smmu.c:arm_smmu_add_device",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_add_device",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_add_device",
        "drivers/iommu/virtio-iommu.c:viommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498823688,
      "name": "iommu_group_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231431692,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_add_device",
        "drivers/iommu/omap-iommu.c:_omap_iommu_add_device",
        "drivers/iommu/omap-iommu.c:omap_iommu_remove",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_add_device",
        "drivers/iommu/tegra-gart.c:gart_iommu_add_device",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_add_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_remove_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_add_device",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231430436,
      "name": "iommu_group_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292036572,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292034832,
      "name": "iommu_group_put",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786360,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785152,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585645544,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644336,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585975400,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974192,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
```

```json
{
  "name": "iommu_group_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586083144,
      "name": "iommu_group_put",
      "external": true,
      "loc": "drivers/iommu/iommu.c:898",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_get_from_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/vfio.c:vfio_iommu_group_put",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081936,
      "name": "iommu_group_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void iommu_group_put(struct iommu_group * group)
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
