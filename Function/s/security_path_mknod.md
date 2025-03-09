# Function: <code>security_path_mknod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236480,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:413",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:SyS_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236480,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455056,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:414",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455056,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547520,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:423",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547520,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633328,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1028",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633328,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786992,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:977",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786992,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983936,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:519",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983936,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583095712,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1040",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:path_openat",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095712,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283776,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1054",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283776,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389600,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389600,
      "name": "security_path_mknod",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727568,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1242",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:may_o_create",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727568,
      "name": "security_path_mknod",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847760,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1244",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:may_o_create",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847760,
      "name": "security_path_mknod",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873600,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1297",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873600,
      "name": "security_path_mknod",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237376,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1297",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237376,
      "name": "security_path_mknod",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584843888,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1317",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843888,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545904,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1315",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545904,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776368,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1824",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776368,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025360,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1897",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025360,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495140048,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495140048,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228527896,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228527896,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289056800,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289056800,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274389988,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274389988,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358336,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358336,
      "name": "security_path_mknod",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295440,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295440,
      "name": "security_path_mknod",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342112,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342112,
      "name": "security_path_mknod",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_path_mknod(const struct path * dir, struct dentry * dentry, umode_t mode, unsigned int dev)
```

```json
{
  "name": "security_path_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437296,
      "name": "security_path_mknod",
      "external": true,
      "loc": "security/security.c:1094",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:lookup_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437296,
      "name": "security_path_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<b>Param type changed. </b>
<code>struct path * dir</code> ➡️ <code>const struct path * dir</code>
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
