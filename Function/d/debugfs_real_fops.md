# Function: <code>debugfs_real_fops</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582425643,
      "name": "debugfs_real_fops",
      "external": false,
      "loc": "include/linux/debugfs.h:56",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582509210,
      "name": "debugfs_real_fops",
      "external": false,
      "loc": "include/linux/debugfs.h:55",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582660776,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:48",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071582659536,
      "name": "debugfs_real_fops.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071582659552,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582854236,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:48",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071582852848,
      "name": "debugfs_real_fops.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071582852864,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582962382,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:48",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071582961120,
      "name": "debugfs_real_fops.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071582961136,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583143231,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:48",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583143659,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583143686,
      "name": "debugfs_real_fops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071583141824,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583249436,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583248000,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583248016,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583575805,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573104,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583696269,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693568,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721053,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718144,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081276,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076736,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584674464,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668768,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358880,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585352016,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585589219,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582176,
      "name": "debugfs_real_fops",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585829411,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:50",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821184,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494976288,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446603336494974560,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336494974592,
      "name": "debugfs_real_fops",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228381688,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 3228379976,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3228380028,
      "name": "debugfs_real_fops",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288856776,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 13835058055288854384,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 13835058055288854416,
      "name": "debugfs_real_fops",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274276656,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446743936274275036,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446743936274275066,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583218172,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583216736,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583216752,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583155324,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583153888,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583153904,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583202204,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583200768,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583200784,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct file_operations * debugfs_real_fops(const struct file * filp)
```

```json
{
  "name": "debugfs_real_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583296092,
      "name": "debugfs_real_fops",
      "external": true,
      "loc": "fs/debugfs/file.c:49",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": [
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_release",
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
      "addr": 18446744071583294656,
      "name": "debugfs_real_fops.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583294672,
      "name": "debugfs_real_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const struct file_operations * debugfs_real_fops(const struct file * filp)
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
