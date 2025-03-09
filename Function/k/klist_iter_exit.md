# Function: <code>klist_iter_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330256,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330256,
      "name": "klist_iter_exit",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587828608,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828608,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588043536,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043536,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588206848,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588206848,
      "name": "klist_iter_exit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756848,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756848,
      "name": "klist_iter_exit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589134944,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589134944,
      "name": "klist_iter_exit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589369792,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:312",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589369792,
      "name": "klist_iter_exit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589826864,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589826864,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053072,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053072,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585047872,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585047872,
      "name": "klist_iter_exit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197696,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197696,
      "name": "klist_iter_exit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585080848,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080848,
      "name": "klist_iter_exit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585527808,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527808,
      "name": "klist_iter_exit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586680832,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586680832,
      "name": "klist_iter_exit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595761232,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595761232,
      "name": "klist_iter_exit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596285600,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285600,
      "name": "klist_iter_exit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597170464,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:do_attribute_container_device_trigger_safe",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597170464,
      "name": "klist_iter_exit",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503828976,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503828976,
      "name": "klist_iter_exit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236448096,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236448096,
      "name": "klist_iter_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297674080,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297674080,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279722390,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279722390,
      "name": "klist_iter_exit",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589655328,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589655328,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381152,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381152,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098704,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098704,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void klist_iter_exit(struct klist_iter * i)
```

```json
{
  "name": "klist_iter_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590149008,
      "name": "klist_iter_exit",
      "external": true,
      "loc": "lib/klist.c:311",
      "file": "lib/klist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_for_each_child_reverse",
        "drivers/base/core.c:device_for_each_child",
        "drivers/base/bus.c:subsys_interface_unregister",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_for_each_drv",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:subsys_find_device_by_id",
        "drivers/base/bus.c:bus_find_device",
        "drivers/base/bus.c:bus_for_each_dev",
        "drivers/base/driver.c:driver_find_device",
        "drivers/base/driver.c:driver_for_each_device",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_find_class_device",
        "drivers/base/attribute_container.c:attribute_container_device_trigger",
        "drivers/base/attribute_container.c:attribute_container_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149008,
      "name": "klist_iter_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
