# Function: <code>dqput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406592,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:734",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406592,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581588816,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:741",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588816,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581677200,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:738",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677200,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734679,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:739",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731104,
      "name": "dqput.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071581731552,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581881624,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:750",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877024,
      "name": "dqput.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    },
    {
      "addr": 18446744071581877472,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582066933,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:747",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063184,
      "name": "dqput.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582063632,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159989,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:747",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156240,
      "name": "dqput.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582156688,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322513,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:753",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318928,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582319376,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582421713,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418016,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582418464,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582716590,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:752",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:remove_dquot_ref",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:remove_dquot_ref",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713680,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582714128,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582787758,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:753",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:remove_dquot_ref",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:remove_dquot_ref",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784848,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582785296,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582815358,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:751",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812432,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582812880,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583145214,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:756",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142000,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071592246552,
      "name": "dqput.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071583142480,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583631117,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:766",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627968,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071594027269,
      "name": "dqput.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071583628464,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236189,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:766",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232912,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071596062745,
      "name": "dqput.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584233424,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466621,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:846",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463472,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071596586778,
      "name": "dqput.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584463776,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689789,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:851",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:invalidate_dquots",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686560,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071597492548,
      "name": "dqput.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584686880,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494024484,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494021072,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446603336494021936,
      "name": "dqput",
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227489172,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227486120,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 3227486728,
      "name": "dqput",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287680112,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287673936,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 13835058055287674912,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273536898,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273532686,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446743936273533390,
      "name": "dqput",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582390449,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386752,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582387200,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582328145,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324448,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582324896,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582380929,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377232,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071582377680,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dqput(struct dquot * dquot)
```

```json
{
  "name": "dqput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582458233,
      "name": "dqput",
      "external": true,
      "loc": "fs/quota/dquot.c:754",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453456,
      "name": "dqput.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071582453904,
      "name": "dqput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
