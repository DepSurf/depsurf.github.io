# Function: <code>aa_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477344,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:132",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file",
        "security/apparmor/mount.c:audit_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477344,
      "name": "aa_audit",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709472,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:132",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file",
        "security/apparmor/mount.c:audit_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709472,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804064,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:132",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file",
        "security/apparmor/mount.c:audit_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804064,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893808,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:129",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893808,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583052128,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:129",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052128,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252752,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:129",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252752,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583370768,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:129",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370768,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583557840,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583557840,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663568,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663568,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024448,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024448,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143888,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:123",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143888,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584171040,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:123",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171040,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555744,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:123",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555744,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198544,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:166",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/task.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198544,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int aa_audit(int type, struct aa_profile * profile, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585928544,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:166",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/task.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928544,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int aa_audit(int type, struct aa_profile * profile, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161024,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:166",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/task.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161024,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int aa_audit(int type, struct aa_profile * profile, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586410272,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:166",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:audit_caps",
        "security/apparmor/task.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410272,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495456600,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495456600,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228823544,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228823544,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289506752,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289506752,
      "name": "aa_audit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274645440,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274645440,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632304,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632304,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569360,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569360,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616080,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616080,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_audit(int type, struct aa_profile * profile, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713936,
      "name": "aa_audit",
      "external": true,
      "loc": "security/apparmor/audit.c:125",
      "file": "security/apparmor/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_may_ptrace",
        "security/apparmor/resource.c:audit_resource",
        "security/apparmor/file.c:aa_audit_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713936,
      "name": "aa_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data * ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data * sa</code>
</li>
</ul>
</details>
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
