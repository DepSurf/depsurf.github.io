# Function: <code>do_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980416,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980416,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135536,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135536,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210624,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210624,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256544,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256544,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395664,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395664,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550272,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550272,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635552,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:path_openat",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635552,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752112,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752112,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824320,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824320,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045744,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:38",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:handle_truncate",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045744,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094736,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:38",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:handle_truncate",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094736,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct user_namespace * mnt_userns, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124944,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:38",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124944,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_truncate(struct user_namespace * mnt_userns, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436400,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:38",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436400,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_truncate(struct user_namespace * mnt_userns, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959504,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:39",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959504,
      "name": "do_truncate",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int do_truncate(struct user_namespace * mnt_userns, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517888,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:39",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517888,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int do_truncate(struct mnt_idmap * idmap, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733328,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733328,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int do_truncate(struct mnt_idmap * idmap, struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934128,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:40",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_open",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934128,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493287624,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493287624,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226891032,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226891032,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286823696,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286823696,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273035100,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273035100,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793056,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793056,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730720,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730720,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784368,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784368,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_truncate(struct dentry * dentry, loff_t length, unsigned int time_attrs, struct file * filp)
```

```json
{
  "name": "do_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853504,
      "name": "do_truncate",
      "external": true,
      "loc": "fs/open.c:41",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_last",
        "fs/coredump.c:dump_truncate",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853504,
      "name": "do_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, length, time_attrs, filp</code> ➡️ <code>mnt_userns, dentry, length, time_attrs, filp</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
