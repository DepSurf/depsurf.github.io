# Function: <code>debugfs_lookup</code>

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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500032,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:261",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500032,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582651248,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:263",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651248,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844752,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:288",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844752,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952928,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:288",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952928,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133408,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:290",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133408,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239616,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239616,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566800,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566800,
      "name": "debugfs_lookup",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688096,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:296",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688096,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712624,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:300",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712624,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584074944,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:300",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/slub.c:debugfs_slab_release",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592289459,
      "name": "debugfs_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584074880,
      "name": "debugfs_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:300",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/slub.c:debugfs_slab_release",
        "drivers/base/component.c:free_aggregate_device",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594071544,
      "name": "debugfs_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584666768,
      "name": "debugfs_lookup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:323",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:debugfs_slab_release",
        "fs/debugfs/inode.c:debugfs_lookup_and_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596091913,
      "name": "debugfs_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585349424,
      "name": "debugfs_lookup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:323",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_lookup_and_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596615277,
      "name": "debugfs_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585579584,
      "name": "debugfs_lookup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:330",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_lookup_and_remove",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597521160,
      "name": "debugfs_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585818336,
      "name": "debugfs_lookup",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494963048,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494963048,
      "name": "debugfs_lookup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228370768,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228370768,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288840864,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288840864,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274264450,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274264450,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208352,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208352,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145504,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145504,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192384,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192384,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
```

```json
{
  "name": "debugfs_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286272,
      "name": "debugfs_lookup",
      "external": true,
      "loc": "fs/debugfs/inode.c:292",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286272,
      "name": "debugfs_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct dentry * debugfs_lookup(const char * name, struct dentry * parent)
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
