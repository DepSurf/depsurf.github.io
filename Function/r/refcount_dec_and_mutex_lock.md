# Function: <code>refcount_dec_and_mutex_lock</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483248,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:306",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483248,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583664272,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:307",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664272,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881952,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:307",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881952,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583966128,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:306",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966128,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584146016,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146016,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268464,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268464,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676016,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
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
        "drivers/vfio/vfio.c:vfio_group_put_bg",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676016,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584793568,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
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
        "drivers/vfio/vfio.c:vfio_group_put_bg",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793568,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584837808,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
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
        "drivers/vfio/vfio.c:vfio_group_put_bg",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837808,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585257227,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
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
        "drivers/vfio/vfio.c:vfio_group_put_bg",
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324578,
      "name": "refcount_dec_and_mutex_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585257184,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/vfio/vfio.c:__vfio_register_dev",
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
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594129054,
      "name": "refcount_dec_and_mutex_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586099680,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
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
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596116070,
      "name": "refcount_dec_and_mutex_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587084400,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
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
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641809,
      "name": "refcount_dec_and_mutex_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587343072,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:113",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:devm_phy_package_leave",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
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
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549874,
      "name": "refcount_dec_and_mutex_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587626592,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496151136,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496151136,
      "name": "refcount_dec_and_mutex_lock",
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229473040,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229473040,
      "name": "refcount_dec_and_mutex_lock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290412848,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290412848,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275205632,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock",
        "net/sched/act_api.c:__tcf_action_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275205632,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584237200,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237200,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172400,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172400,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220960,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220960,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```

```json
{
  "name": "refcount_dec_and_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325792,
      "name": "refcount_dec_and_mutex_lock",
      "external": true,
      "loc": "lib/refcount.c:314",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_bus_put",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_put_opp_list_kref",
        "net/core/rtnetlink.c:refcount_dec_and_rtnl_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325792,
      "name": "refcount_dec_and_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t * r, struct mutex * lock)
```
</details>
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
