# Function: <code>cred_has_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, int audit)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582279808,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1586",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_getsecurity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279808,
      "name": "cred_has_capability.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582281520,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int cred_has_capability(const struct cred * cred, int cap, int audit, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500768,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1657",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500768,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int cred_has_capability(const struct cred * cred, int cap, int audit, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593616,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1665",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593616,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int cred_has_capability(const struct cred * cred, int cap, int audit, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582684208,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1664",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684208,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int cred_has_capability(const struct cred * cred, int cap, int audit, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839792,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1668",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839792,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int cred_has_capability(const struct cred * cred, int cap, int audit, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023232,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1767",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023232,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139744,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1582",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139744,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1626",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327600,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071583351582,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432960,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583457550,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583776202,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1581",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771168,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583800710,
      "name": "cred_has_capability.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583896330,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1590",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890848,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071591363120,
      "name": "cred_has_capability.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922010,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1649",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917232,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071591305903,
      "name": "cred_has_capability.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584286090,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1641",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280304,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071592294112,
      "name": "cred_has_capability.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584906478,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1579",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897568,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071594076143,
      "name": "cred_has_capability.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585615246,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1578",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605216,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585843731,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1592",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835840,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586094470,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1634",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_vm_enough_memory"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085840,
      "name": "cred_has_capability.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495192064,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495192064,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228591300,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228591300,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289156896,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289156896,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274430194,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274430194,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401696,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583426286,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338768,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583363358,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385472,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583410062,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
```

```json
{
  "name": "cred_has_capability",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cred_has_capability",
      "external": false,
      "loc": "security/selinux/hooks.c:1628",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/hooks.c:selinux_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494496,
      "name": "cred_has_capability",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583506577,
      "name": "cred_has_capability.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool initns</code>
</li>
</ul>
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
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int audit</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cred_has_capability(const struct cred * cred, int cap, unsigned int opts, bool initns)
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
