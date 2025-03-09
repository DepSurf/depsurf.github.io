# Function: <code>tracefs_remove_recursive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119552,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:562",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:event_trace_del_tracer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119552,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337856,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:559",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337856,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428672,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:559",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428672,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512208,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:557",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512208,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663840,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:557",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663840,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582857296,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:557",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857296,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965472,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:558",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_rmdir",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965472,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583146400,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:557",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583146400,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252496,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252496,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494979824,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494979824,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228385728,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228385728,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288861248,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288861248,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274279840,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274279840,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221232,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221232,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158384,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158384,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205264,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205264,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void tracefs_remove_recursive(struct dentry * dentry)
```

```json
{
  "name": "tracefs_remove_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299152,
      "name": "tracefs_remove_recursive",
      "external": true,
      "loc": "fs/tracefs/inode.c:561",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299152,
      "name": "tracefs_remove_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tracefs_remove_recursive(struct dentry * dentry)
```
</details>
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
