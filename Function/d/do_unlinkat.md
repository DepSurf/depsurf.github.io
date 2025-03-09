# Function: <code>do_unlinkat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_unlinkat(int dfd, const char * pathname)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059504,
      "name": "do_unlinkat",
      "external": false,
      "loc": "fs/namei.c:3839",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:SyS_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059504,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
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
long int do_unlinkat(int dfd, const char * pathname)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220480,
      "name": "do_unlinkat",
      "external": false,
      "loc": "fs/namei.c:3982",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220480,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
long int do_unlinkat(int dfd, const char * pathname)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298144,
      "name": "do_unlinkat",
      "external": false,
      "loc": "fs/namei.c:3939",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298144,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
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
long int do_unlinkat(int dfd, const char * pathname)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347680,
      "name": "do_unlinkat",
      "external": false,
      "loc": "fs/namei.c:4004",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347680,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491968,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4002",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491968,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653200,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4036",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653200,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739520,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4025",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739520,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856080,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4026",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856080,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928544,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928544,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158528,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:3852",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158528,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204464,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:3853",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204464,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229248,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4052",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229248,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582546096,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546096,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074064,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4224",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump",
        "io_uring/io_uring.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074064,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640752,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4280",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640752,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857920,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4357",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857920,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064912,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4366",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064912,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493409320,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__arm64_sys_unlink",
        "fs/namei.c:__arm64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493409320,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226994940,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226994940,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286968432,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286968432,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273120048,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273120048,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897280,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897280,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834880,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834880,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888592,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888592,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
long int do_unlinkat(int dfd, struct filename * name)
```

```json
{
  "name": "do_unlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958096,
      "name": "do_unlinkat",
      "external": true,
      "loc": "fs/namei.c:4021",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958096,
      "name": "do_unlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
<b>Param added. </b>
<code>struct filename * name</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * pathname</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
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
