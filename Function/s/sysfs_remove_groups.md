# Function: <code>sysfs_remove_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522416,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:261",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522416,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708368,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:261",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708368,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796224,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:261",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796224,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581851184,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:261",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851184,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582001008,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:261",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001008,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582189056,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:265",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189056,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284080,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:280",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284080,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582448928,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:304",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448928,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582548112,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548112,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582855216,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:__kobject_del",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855216,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582928272,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:__kobject_del",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928272,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582955920,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:__kobject_del",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955920,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583291168,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_destroy_sysfs",
        "lib/kobject.c:__kobject_del",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291168,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583797648,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:304",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:__kobject_del",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797648,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584417984,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:304",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:alloc_dax_region",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417984,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584646576,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:308",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646576,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584878960,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:308",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878960,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494187176,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_remove",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494187176,
      "name": "sysfs_remove_groups",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227624388,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227624388,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287876640,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287876640,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273650718,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273650718,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582516848,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516848,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582454016,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454016,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582507328,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507328,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void sysfs_remove_groups(struct kobject * kobj, const struct attribute_group * * groups)
```

```json
{
  "name": "sysfs_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582588224,
      "name": "sysfs_remove_groups",
      "external": true,
      "loc": "fs/sysfs/group.c:305",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:devm_attr_groups_remove",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/dax/bus.c:dax_region_unregister",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588224,
      "name": "sysfs_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
