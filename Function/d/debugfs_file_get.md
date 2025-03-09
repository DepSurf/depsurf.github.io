# Function: <code>debugfs_file_get</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655664,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:80",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655664,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849200,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:80",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849200,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957488,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:80",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957488,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138304,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:80",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138304,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244480,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244480,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573200,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573200,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693664,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693664,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718240,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718240,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079104,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079104,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584671984,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584671984,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585356160,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write_signed",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356160,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586320,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write_signed",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586320,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825760,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:82",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:write_file_blob",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_str",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write_signed",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825760,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494968752,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494968752,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228380468,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228380468,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288848112,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288848112,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274269614,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274269614,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213216,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213216,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150368,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150368,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197248,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197248,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int debugfs_file_get(struct dentry * dentry)
```

```json
{
  "name": "debugfs_file_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291136,
      "name": "debugfs_file_get",
      "external": true,
      "loc": "fs/debugfs/file.c:81",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291136,
      "name": "debugfs_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int debugfs_file_get(struct dentry * dentry)
```
</details>
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
