# Function: <code>kernel_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194848,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/splice.c:588",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_intvec",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194848,
      "name": "kernel_write",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358896,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/splice.c:589",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358896,
      "name": "kernel_write",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438336,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/splice.c:370",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438336,
      "name": "kernel_write",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492976,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/splice.c:367",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492976,
      "name": "kernel_write",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417600,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:537",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417600,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576688,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:542",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576688,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662448,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:542",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662448,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581770592,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770592,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842816,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842816,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065872,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:575",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065872,
      "name": "kernel_write",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582112448,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:570",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112448,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136368,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:569",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136368,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582453040,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:559",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453040,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978000,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:555",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978000,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541840,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:548",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541840,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757744,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:548",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757744,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583960368,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:554",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960368,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493307728,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493307728,
      "name": "kernel_write",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226910580,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226910580,
      "name": "kernel_write",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286848416,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286848416,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273049424,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273049424,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811552,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811552,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749216,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749216,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802864,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802864,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_write(struct file * file, const void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872080,
      "name": "kernel_write",
      "external": true,
      "loc": "fs/read_write.c:551",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872080,
      "name": "kernel_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char * buf</code> ➡️ <code>const void * buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>loff_t pos</code> ➡️ <code>loff_t * pos</code>
</li>
</ul>
</details>
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
