# Function: <code>propagate_mount_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192688,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:337",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192688,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356736,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:345",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356736,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435632,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:358",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435632,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489696,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:376",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489696,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631648,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:376",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631648,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790272,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:376",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790272,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581877168,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:377",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877168,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002080,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002080,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080032,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080032,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316016,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316016,
      "name": "propagate_mount_busy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368944,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368944,
      "name": "propagate_mount_busy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582396272,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396272,
      "name": "propagate_mount_busy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717808,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717808,
      "name": "propagate_mount_busy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262464,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262464,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844160,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:369",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844160,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062400,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:407",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062400,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584277536,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:407",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277536,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493614696,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493614696,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227156972,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227156972,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287201216,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287201216,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273259358,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273259358,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048768,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048768,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986320,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986320,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040048,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040048,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int propagate_mount_busy(struct mount * mnt, int refcnt)
```

```json
{
  "name": "propagate_mount_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111776,
      "name": "propagate_mount_busy",
      "external": true,
      "loc": "fs/pnode.c:370",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:may_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111776,
      "name": "propagate_mount_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
