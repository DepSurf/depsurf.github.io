# Function: <code>unlock_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034144,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2640",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034144,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194352,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2861",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194352,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271568,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2825",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271568,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581325712,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2870",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325712,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581465872,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2868",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465872,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581622160,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2869",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622160,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708544,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2888",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708544,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581826832,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2886",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826832,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899392,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899392,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154475,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2781",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128624,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206486,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2779",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175120,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582231459,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2872",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198736,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582549821,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2941",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516064,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583078202,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:3037",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040192,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645162,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:3016",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605552,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583862360,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:3093",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824016,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584069399,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:3120",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030080,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493379512,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493379512,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226968576,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226968576,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286932640,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286932640,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273096764,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273096764,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581868128,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868128,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805728,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805728,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581859440,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859440,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void unlock_rename(struct dentry * p1, struct dentry * p2)
```

```json
{
  "name": "unlock_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581930800,
      "name": "unlock_rename",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930800,
      "name": "unlock_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
