# Function: <code>lookup_one_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040752,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2287",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_unlink",
        "security/inode.c:securityfs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040752,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200464,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2426",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200464,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277728,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2415",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277728,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326464,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2460",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aafs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326464,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466592,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2458",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_lookup",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466592,
      "name": "lookup_one_len",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629520,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2506",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629520,
      "name": "lookup_one_len",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715696,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2530",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715696,
      "name": "lookup_one_len",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833216,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2528",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833216,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905680,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905680,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138240,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2549",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138240,
      "name": "lookup_one_len",
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184832,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2547",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_iter_link_pin_kernel",
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184832,
      "name": "lookup_one_len",
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207040,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2637",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207040,
      "name": "lookup_one_len",
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524832,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2673",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524832,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046368,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2719",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046368,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583611920,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2698",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/tracefs/inode.c:start_creating",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611920,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827728,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2729",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827728,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033776,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2746",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_rename",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033776,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493386376,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493386376,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226970672,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226970672,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286938032,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286938032,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273102082,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273102082,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874416,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874416,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812016,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812016,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865728,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865728,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct dentry * lookup_one_len(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_one_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935184,
      "name": "lookup_one_len",
      "external": true,
      "loc": "fs/namei.c:2521",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/debugfs/inode.c:start_creating",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935184,
      "name": "lookup_one_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
