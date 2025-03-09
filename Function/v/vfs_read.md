# Function: <code>vfs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993264,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:440",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_pread64",
        "fs/exec.c:kernel_read",
        "fs/exec.c:read_code",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993264,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149968,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:460",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pread64",
        "fs/read_write.c:SyS_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149968,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226640,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:460",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pread64",
        "fs/read_write.c:SyS_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226640,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581272832,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:418",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pread64",
        "fs/read_write.c:SyS_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272832,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581416496,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pread64",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416496,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581575536,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:437",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575536,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581661264,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:437",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661264,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779152,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779152,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581851376,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851376,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065088,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:461",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065088,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111616,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:476",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111616,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145616,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:476",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145616,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453488,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:465",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453488,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981824,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:462",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981824,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539760,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:450",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539760,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755568,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:450",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755568,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958080,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:456",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958080,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493318304,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493318304,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226914604,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226914604,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286857984,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286857984,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273052372,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273052372,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820112,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820112,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581757776,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757776,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581811424,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811424,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t vfs_read(struct file * file, char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581880640,
      "name": "vfs_read",
      "external": true,
      "loc": "fs/read_write.c:446",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pread64",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:kernel_read",
        "fs/exec.c:read_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880640,
      "name": "vfs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
