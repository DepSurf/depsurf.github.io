# Function: <code>class_to_subsys</code>

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
struct subsys_private * class_to_subsys(const struct class * class)
```

```json
{
  "name": "class_to_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621600,
      "name": "class_to_subsys",
      "external": true,
      "loc": "drivers/base/class.c:42",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_is_registered",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/base/class.c:class_create_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621600,
      "name": "class_to_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct subsys_private * class_to_subsys(const struct class * class)
```

```json
{
  "name": "class_to_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590980848,
      "name": "class_to_subsys",
      "external": true,
      "loc": "drivers/base/class.c:42",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_is_registered",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_unregister",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_find_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/class.c:class_for_each_device",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/base/class.c:class_create_file_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590980848,
      "name": "class_to_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct subsys_private * class_to_subsys(const struct class * class)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
