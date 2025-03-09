# Function: <code>readlink_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034768,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4488",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:generic_readlink",
        "fs/namei.c:page_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/self.c:proc_self_readlink",
        "fs/proc/thread_self.c:proc_thread_self_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034768,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229488,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:generic_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/self.c:proc_self_readlink",
        "fs/proc/thread_self.c:proc_thread_self_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229488,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307184,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4586",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307184,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356544,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4652",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356544,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498016,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4648",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498016,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581622402,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4700",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink"
      ],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622240,
      "name": "readlink_copy.part.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071581655600,
      "name": "readlink_copy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708786,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4689",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink"
      ],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708624,
      "name": "readlink_copy.part.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071581741888,
      "name": "readlink_copy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858480,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4690",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858480,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930944,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930944,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160992,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4499",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160992,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207424,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4503",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207424,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232400,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4749",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232400,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582550896,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4829",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550896,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079424,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4924",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079424,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583646512,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4980",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583646512,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863712,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:5059",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863712,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070752,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:5091",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070752,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493411496,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493411496,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226997228,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226997228,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286971408,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286971408,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273122226,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273122226,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899680,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899680,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837280,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837280,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890992,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890992,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int readlink_copy(char * buffer, int buflen, const char * link)
```

```json
{
  "name": "readlink_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960496,
      "name": "readlink_copy",
      "external": true,
      "loc": "fs/namei.c:4685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:page_readlink",
        "fs/namei.c:vfs_readlink",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "security/apparmor/apparmorfs.c:policy_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960496,
      "name": "readlink_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
