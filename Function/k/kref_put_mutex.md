# Function: <code>kref_put_mutex</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587052875,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:76",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586426293,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:76",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587351333,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:76",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586571781,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:73",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587530469,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:73",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586823285,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587805013,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586969381,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587038577,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587067033,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588010021,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587794264,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587873619,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909063,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588876561,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_prop_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863808,
      "name": "kref_put_mutex.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587852312,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587934051,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587970711,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588883718,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_bw",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_prop_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878768,
      "name": "kref_put_mutex.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int kref_put_mutex(struct kref * kref, void (*)(struct kref *) release, struct mutex * lock)
```

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587731720,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817123,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587852340,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588769394,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_prop_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765120,
      "name": "kref_put_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int kref_put_mutex(struct kref * kref, void (*)(struct kref *) release, struct mutex * lock)
```

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588325224,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588420835,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589461088,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_prop_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456208,
      "name": "kref_put_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589715699,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590938609,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_prop_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934272,
      "name": "kref_put_mutex.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591332755,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592641857,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592636960,
      "name": "kref_put_mutex.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591694275,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593072350,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
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
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592437299,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593825104,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add_dynamic",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499960768,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501265864,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232499652,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 3233756516,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293286116,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293363800,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293397164,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294786656,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277039774,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277942668,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586726389,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587635013,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586593605,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586686497,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586714953,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587408885,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586923941,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586993137,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587021593,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587966165,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kref_put_mutex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587030389,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587100305,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128761,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588081541,
      "name": "kref_put_mutex",
      "external": false,
      "loc": "include/linux/kref.h:71",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int kref_put_mutex(struct kref * kref, void (*)(struct kref *) release, struct mutex * lock)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int kref_put_mutex(struct kref * kref, void (*)(struct kref *) release, struct mutex * lock)
```
</details>
</li>
</ul>
