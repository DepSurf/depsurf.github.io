# Function: <code>config_item_put</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867104,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:178",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_release",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_put",
        "fs/configfs/item.c:config_item_put",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867104,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582017191,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:178",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/file.c:configfs_release",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017296,
      "name": "config_item_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582205607,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:178",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/file.c:configfs_release",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205712,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582300615,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:162",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/file.c:configfs_release",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300720,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582466946,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467056,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582565890,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566000,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582874098,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/file.c:__configfs_open_file",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874240,
      "name": "config_item_put",
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582946962,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947104,
      "name": "config_item_put",
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582974450,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974592,
      "name": "config_item_put",
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583310047,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:client_drop_item",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310192,
      "name": "config_item_put",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583817229,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817040,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071583817296,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584439181,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438976,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584439264,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584667949,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667744,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584668032,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900717,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:146",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:unlink_group",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900512,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584900800,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494211280,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494211280,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446603336494211488,
      "name": "config_item_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227642732,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:__configfs_open_file",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227642732,
      "name": "config_item_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 3227642936,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287905376,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:__configfs_open_file",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:client_drop_item",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/item.c:config_item_put",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287905376,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273669726,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ],
      "caller_func": [
        "fs/configfs/file.c:__configfs_open_file",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273669844,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582534626,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534736,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471794,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471904,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582525106,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525216,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
```

```json
{
  "name": "config_item_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582605778,
      "name": "config_item_put",
      "external": true,
      "loc": "fs/configfs/item.c:148",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release",
        "fs/configfs/item.c:config_item_release"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:unlink_obj",
        "fs/configfs/dir.c:configfs_remove_default_groups",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605888,
      "name": "config_item_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void config_item_put(struct config_item * item)
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
