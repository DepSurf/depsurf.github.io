# Function: <code>shmem_kernel_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597088,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:3413",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597088,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697936,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4174",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697936,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763712,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4068",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763712,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799728,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4233",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799728,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580888501,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4279",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888432,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581024197,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:3995",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024128,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096485,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:3954",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101888,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581150202,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4035",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166272,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208090,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224192,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581408789,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4120",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411776,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581453925,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4227",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454496,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581475109,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4171",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475392,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581726661,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4107",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729456,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108901,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4119",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108832,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582582773,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4248",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582688,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582789861,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4457",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789776,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582964741,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4832",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964656,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492591568,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492610600,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226444880,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464556,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285900228,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285929520,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272627274,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup"
      ],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639430,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176938,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193040,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123754,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139792,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581168138,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184240,
      "name": "shmem_kernel_file_setup",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_kernel_file_setup(const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_kernel_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224890,
      "name": "shmem_kernel_file_setup",
      "external": true,
      "loc": "mm/shmem.c:4157",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob",
        "ipc/shm.c:newseg",
        "security/keys/big_key.c:big_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247488,
      "name": "shmem_kernel_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
