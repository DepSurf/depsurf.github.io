# Function: <code>simple_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154944,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:472",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154944,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int simple_fill_super(struct super_block * s, long unsigned int magic, struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320368,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:500",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320368,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int simple_fill_super(struct super_block * s, long unsigned int magic, struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399584,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:508",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399584,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454976,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:509",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454976,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596928,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:509",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596928,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:509",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760135,
      "name": "simple_fill_super.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581754848,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:509",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846663,
      "name": "simple_fill_super.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581841376,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:528",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971271,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581965936,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044519,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582038688,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:602",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280839,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582274032,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:604",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340048,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582324032,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:607",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282799,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582351968,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:616",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231052,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582672608,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:643",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594010993,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583215392,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793328,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:644",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793328,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584010944,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:639",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010944,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232560,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:916",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "fs/debugfs/inode.c:debug_fill_super",
        "fs/tracefs/inode.c:trace_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232560,
      "name": "simple_fill_super",
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493564144,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493564144,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227112400,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227112400,
      "name": "simple_fill_super",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287141216,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287141216,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273221964,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273221964,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013255,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582007424,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950823,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581944992,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004535,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581998704,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int simple_fill_super(struct super_block * s, long unsigned int magic, const struct tree_descr * files)
```

```json
{
  "name": "simple_fill_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "simple_fill_super",
      "external": true,
      "loc": "fs/libfs.c:533",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_fill_super",
        "security/inode.c:securityfs_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/smack/smackfs.c:smk_fill_super",
        "security/apparmor/apparmorfs.c:apparmorfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075063,
      "name": "simple_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582069664,
      "name": "simple_fill_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tree_descr * files</code> ➡️ <code>const struct tree_descr * files</code>
</li>
</ul>
</details>
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
