# Function: <code>vfs_copy_file_range</code>

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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154752,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1505",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154752,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581231440,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1534",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231440,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278064,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1545",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278064,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415648,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1548",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415648,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573664,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1575",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573664,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 783
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659312,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1571",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659312,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777248,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777248,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849472,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849472,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074720,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1735",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074720,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124144,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1473",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124144,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148752,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1478",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148752,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465584,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1469",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465584,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1130
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985488,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1479",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985488,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1296
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545792,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1476",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545792,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1371
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761728,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1475",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761728,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1490
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964416,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1483",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__do_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964416,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1495
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493315720,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493315720,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226913540,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226913540,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286856160,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286856160,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273051652,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273051652,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818208,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818208,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755872,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755872,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809520,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809520,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "vfs_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878736,
      "name": "vfs_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1651",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878736,
      "name": "vfs_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
ssize_t vfs_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
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
