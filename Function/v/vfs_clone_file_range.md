# Function: <code>vfs_clone_file_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146432,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1648",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146432,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225296,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1801",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225296,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271472,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1817",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271472,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410416,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1820",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410416,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566112,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1847",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566112,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650592,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2024",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650592,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767808,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2097",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767808,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840016,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840016,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064400,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2179",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064400,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410576,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:417",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410576,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437376,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:417",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437376,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760160,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:405",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760160,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311248,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:395",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311248,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896192,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:404",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896192,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584118128,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:407",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118128,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335408,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:376",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335408,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493305128,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493305128,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226906944,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226906944,
      "name": "vfs_clone_file_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286844128,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286844128,
      "name": "vfs_clone_file_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273048472,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273048472,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808752,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808752,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746416,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746416,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800064,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800064,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869232,
      "name": "vfs_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2095",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ioctl_file_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869232,
      "name": "vfs_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int vfs_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, u64 len)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int remap_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>u64 len</code> ➡️ <code>loff_t len</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>loff_t</code>
</li>
</ul>
</details>
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
