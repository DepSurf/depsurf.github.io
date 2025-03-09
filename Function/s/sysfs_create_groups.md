# Function: <code>sysfs_create_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522288,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:173",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522288,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708240,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:173",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708240,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796096,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:173",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796096,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581851008,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:173",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851008,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000832,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:173",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000832,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188896,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:177",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188896,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284160,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:191",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284160,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449168,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:211",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449168,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548352,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548352,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582855456,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "lib/kobject.c:create_dir",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855456,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928512,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "lib/kobject.c:create_dir",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928512,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956160,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "lib/kobject.c:create_dir",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956160,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291408,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "kernel/irq/msi.c:msi_populate_sysfs",
        "lib/kobject.c:create_dir",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291408,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796096,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:211",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "lib/kobject.c:kobject_add_internal",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796096,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416288,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:211",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416288,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644896,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:215",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644896,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877280,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:215",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877280,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494187456,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494187456,
      "name": "sysfs_create_groups",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227624600,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227624600,
      "name": "sysfs_create_groups",
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287877072,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287877072,
      "name": "sysfs_create_groups",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273650946,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273650946,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517088,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517088,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454256,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454256,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507568,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507568,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sysfs_create_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_create_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588464,
      "name": "sysfs_create_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:212",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_init",
        "drivers/pci/msi.c:populate_msi_sysfs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588464,
      "name": "sysfs_create_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
