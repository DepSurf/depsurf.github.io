# Function: <code>parse_monolithic_mount_data</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035200,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:710",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035200,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112992,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112992,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349984,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:641",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349984,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401936,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:641",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401936,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429168,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:641",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429168,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751920,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:659",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751920,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299472,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:659",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299472,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884416,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:659",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884416,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106192,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:681",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106192,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322448,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:711",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322448,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493653592,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493653592,
      "name": "parse_monolithic_mount_data",
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227188008,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227188008,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287248224,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287248224,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273284372,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273284372,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081728,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081728,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019248,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019248,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073008,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073008,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```

```json
{
  "name": "parse_monolithic_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144768,
      "name": "parse_monolithic_mount_data",
      "external": true,
      "loc": "fs/fs_context.c:696",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144768,
      "name": "parse_monolithic_mount_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int parse_monolithic_mount_data(struct fs_context * fc, void * data)
```
</details>
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
