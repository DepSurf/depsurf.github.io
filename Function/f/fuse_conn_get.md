# Function: <code>fuse_conn_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582099872,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:637",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_alloc"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099872,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582319933,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_alloc"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315632,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582408349,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:648",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_alloc"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403984,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582492285,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:641",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_alloc"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487728,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638928,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:641",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_alloc",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638928,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582832384,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:644",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_alloc",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832384,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935760,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_alloc",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935760,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116032,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:645",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_alloc",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116032,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221632,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221632,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583555797,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:662",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552064,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583667233,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:738",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663184,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688289,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:778",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684224,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049553,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:831",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043424,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638926,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:873",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633072,
      "name": "fuse_conn_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585319494,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:886",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313472,
      "name": "fuse_conn_get",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585549435,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:886",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585543408,
      "name": "fuse_conn_get",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585787764,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:962",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781216,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494948908,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_install"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494943664,
      "name": "fuse_conn_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228352928,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_install"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228352868,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288816164,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_install"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288815920,
      "name": "fuse_conn_get",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274252846,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_install"
      ],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274247404,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190368,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190368,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127520,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127520,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174400,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174400,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fuse_conn * fuse_conn_get(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268128,
      "name": "fuse_conn_get",
      "external": true,
      "loc": "fs/fuse/inode.c:647",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/control.c:fuse_ctl_file_conn_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268128,
      "name": "fuse_conn_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
