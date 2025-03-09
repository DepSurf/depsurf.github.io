# Function: <code>bus_to_subsys</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct subsys_private * bus_to_subsys(const struct bus_type * bus)
```

```json
{
  "name": "bus_to_subsys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590600496,
      "name": "bus_to_subsys",
      "external": false,
      "loc": "drivers/base/bus.c:60",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_get_dev_root",
        "drivers/base/bus.c:bus_is_registered",
        "drivers/base/bus.c:driver_find",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_sort_breadthfirst",
        "drivers/base/bus.c:bus_get_kset",
        "drivers/base/bus.c:bus_notify",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_uevent_store",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_probe_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:drivers_autoprobe_store",
        "drivers/base/bus.c:drivers_autoprobe_show",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590600496,
      "name": "bus_to_subsys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct subsys_private * bus_to_subsys(const struct bus_type * bus)
```

```json
{
  "name": "bus_to_subsys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590959440,
      "name": "bus_to_subsys",
      "external": false,
      "loc": "drivers/base/bus.c:60",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_get_dev_root",
        "drivers/base/bus.c:bus_is_registered",
        "drivers/base/bus.c:driver_find",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_sort_breadthfirst",
        "drivers/base/bus.c:bus_get_kset",
        "drivers/base/bus.c:bus_notify",
        "drivers/base/bus.c:bus_unregister_notifier",
        "drivers/base/bus.c:bus_register_notifier",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_uevent_store",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_probe_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:drivers_autoprobe_store",
        "drivers/base/bus.c:drivers_autoprobe_show",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590959440,
      "name": "bus_to_subsys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct subsys_private * bus_to_subsys(const struct bus_type * bus)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
