# Function: <code>vfs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993568,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:547",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_pwrite64",
        "fs/splice.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993568,
      "name": "vfs_write",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581150272,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:568",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_write",
        "fs/splice.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150272,
      "name": "vfs_write",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226944,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:568",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_write",
        "fs/splice.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226944,
      "name": "vfs_write",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581273136,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:526",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_write",
        "fs/splice.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273136,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417184,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:553",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417184,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576256,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:558",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576256,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581662016,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:558",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662016,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581770176,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770176,
      "name": "vfs_write",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581842400,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842400,
      "name": "vfs_write",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066064,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:591",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066064,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112704,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:586",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112704,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146400,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:585",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146400,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454288,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:575",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454288,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982656,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:571",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982656,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583542304,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:564",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542304,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583758208,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:564",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758208,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960832,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:570",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960832,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493307272,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493307272,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226910124,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226910124,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286847744,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286847744,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273049070,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273049070,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581811136,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811136,
      "name": "vfs_write",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581748800,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_string",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748800,
      "name": "vfs_write",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802448,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802448,
      "name": "vfs_write",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_write(struct file * file, const char * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "vfs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581871664,
      "name": "vfs_write",
      "external": true,
      "loc": "fs/read_write.c:567",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:kernel_write",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871664,
      "name": "vfs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
