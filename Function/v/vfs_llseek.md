# Function: <code>vfs_llseek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580990032,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:251",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:compat_SyS_lseek",
        "fs/read_write.c:SyS_llseek"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990032,
      "name": "vfs_llseek",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149657,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:292",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144912,
      "name": "vfs_llseek",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226329,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:292",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220096,
      "name": "vfs_llseek",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581272521,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:290",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267216,
      "name": "vfs_llseek",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581411465,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406368,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562180,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561248,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647348,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646416,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581765955,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763168,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581838163,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835376,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582061643,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058128,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582109307,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107968,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582134253,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132912,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582450909,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449568,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582969875,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968272,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583529663,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:285",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/coredump.c:__dump_skip",
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527568,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583747471,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:285",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/coredump.c:__dump_skip",
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742960,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583946847,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:285",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/coredump.c:__dump_skip",
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944848,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493306220,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__arm64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493298808,
      "name": "vfs_llseek",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226909544,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__se_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226901652,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286841680,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__se_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286838000,
      "name": "vfs_llseek",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273048714,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273043316,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581806899,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804112,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581744563,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741776,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581798211,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795424,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
loff_t vfs_llseek(struct file * file, loff_t offset, int whence)
```

```json
{
  "name": "vfs_llseek",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867379,
      "name": "vfs_llseek",
      "external": true,
      "loc": "fs/read_write.c:291",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek"
      ],
      "caller_func": [
        "fs/ecryptfs/file.c:ecryptfs_dir_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864592,
      "name": "vfs_llseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
