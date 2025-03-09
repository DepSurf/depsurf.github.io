# Function: <code>__shmem_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * __shmem_file_setup(const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581328,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:3347",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:SyS_memfd_create",
        "mm/shmem.c:shmem_kernel_file_setup",
        "mm/shmem.c:shmem_zero_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581328,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
struct file * __shmem_file_setup(const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675616,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4108",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_kernel_file_setup",
        "mm/shmem.c:SyS_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675616,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
struct file * __shmem_file_setup(const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740224,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4002",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_kernel_file_setup",
        "mm/shmem.c:SyS_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740224,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580799803,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4167",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_kernel_file_setup",
        "mm/shmem.c:SyS_memfd_create",
        "mm/shmem.c:SyS_memfd_create"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_kernel_file_setup",
        "mm/shmem.c:SyS_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779120,
      "name": "__shmem_file_setup.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580888522,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4213",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:SyS_memfd_create"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:SyS_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866512,
      "name": "__shmem_file_setup.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581024214,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:3929",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009056,
      "name": "__shmem_file_setup.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096380,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:3911",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096048,
      "name": "__shmem_file_setup.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581150076,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:3992",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149744,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581207964,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207632,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581408336,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4077",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408336,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581436816,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4184",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436816,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581457216,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4128",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457216,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581710928,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4064",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710928,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582082928,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4076",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082928,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582560512,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4205",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560512,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582762976,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4411",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762976,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582943968,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4786",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943968,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492591332,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492590960,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226444372,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup_with_mnt",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226444372,
      "name": "__shmem_file_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285900228,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285899552,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272627282,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272626790,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176812,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176480,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123628,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123296,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581168012,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167680,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__shmem_file_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224764,
      "name": "__shmem_file_setup",
      "external": false,
      "loc": "mm/shmem.c:4114",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_setup"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224432,
      "name": "__shmem_file_setup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct file * __shmem_file_setup(const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct file * __shmem_file_setup(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags, unsigned int i_flags)
```
</details>
</li>
</ul>
