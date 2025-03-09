# Function: <code>do_mknodat</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581651568,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3753",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651568,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581737840,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3742",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737840,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854512,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3741",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854512,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926976,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926976,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582153368,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3567",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152576,
      "name": "do_mknodat.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
    },
    {
      "addr": 18446744071582157392,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582200024,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:3569",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199120,
      "name": "do_mknodat.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582224744,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:3718",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223808,
      "name": "do_mknodat.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541296,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:3787",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541296,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068768,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:3881",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068768,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583635008,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:3939",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583635008,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849488,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:4019",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849488,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056576,
      "name": "do_mknodat",
      "external": false,
      "loc": "fs/namei.c:4028",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056576,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493407712,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__arm64_sys_mknod",
        "fs/namei.c:__arm64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493407712,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226993416,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mknod",
        "fs/namei.c:__se_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226993416,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286966384,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mknod",
        "fs/namei.c:__se_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286966384,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273118634,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mknod",
        "fs/namei.c:__se_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273118634,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895712,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895712,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581833312,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833312,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581887024,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887024,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```

```json
{
  "name": "do_mknodat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581956528,
      "name": "do_mknodat",
      "external": true,
      "loc": "fs/namei.c:3736",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956528,
      "name": "do_mknodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int do_mknodat(int dfd, const char * filename, umode_t mode, unsigned int dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int do_mknodat(int dfd, struct filename * name, umode_t mode, unsigned int dev)
```
</details>
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
