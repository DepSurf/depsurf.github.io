# Function: <code>__mnt_is_readonly</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121888,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:do_mount"
      ],
      "caller_func": [
        "fs/open.c:SyS_access",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:do_mount",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121888,
      "name": "__mnt_is_readonly.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581121920,
      "name": "__mnt_is_readonly",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300647,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:SyS_access",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287616,
      "name": "__mnt_is_readonly.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581287648,
      "name": "__mnt_is_readonly",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581379639,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:273",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:SyS_access",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366784,
      "name": "__mnt_is_readonly.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581366816,
      "name": "__mnt_is_readonly",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434843,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:SyS_access",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421744,
      "name": "__mnt_is_readonly.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581421776,
      "name": "__mnt_is_readonly",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576721,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:SyS_access",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563248,
      "name": "__mnt_is_readonly.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581563280,
      "name": "__mnt_is_readonly",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732608,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719616,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581819359,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:249",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803920,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944165,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922784,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016775,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995184,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582236788,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229280,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582285588,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277648,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582329091,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:267",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303184,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582649620,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:268",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622240,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583188705,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:269",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157680,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583764041,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:384",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731792,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583981193,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:270",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948688,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584193721,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:275",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_get_write_access"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156128,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493537956,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493513064,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227088348,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227067540,
      "name": "__mnt_is_readonly",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287107792,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287076304,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273202538,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273182692,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581985511,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963920,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581923079,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901488,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976791,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955200,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool __mnt_is_readonly(struct vfsmount * mnt)
```

```json
{
  "name": "__mnt_is_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582047287,
      "name": "__mnt_is_readonly",
      "external": true,
      "loc": "fs/namespace.c:246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write"
      ],
      "caller_func": [
        "fs/open.c:do_faccessat",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025488,
      "name": "__mnt_is_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
