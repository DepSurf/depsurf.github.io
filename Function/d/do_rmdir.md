# Function: <code>do_rmdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058992,
      "name": "do_rmdir",
      "external": false,
      "loc": "fs/namei.c:3711",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rmdir",
        "fs/namei.c:SyS_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058992,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219888,
      "name": "do_rmdir",
      "external": false,
      "loc": "fs/namei.c:3854",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:SyS_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219888,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297584,
      "name": "do_rmdir",
      "external": false,
      "loc": "fs/namei.c:3811",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:SyS_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297584,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347152,
      "name": "do_rmdir",
      "external": false,
      "loc": "fs/namei.c:3876",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:SyS_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347152,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488544,
      "name": "do_rmdir",
      "external": false,
      "loc": "fs/namei.c:3874",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:SyS_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488544,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652656,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3908",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652656,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738928,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3897",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738928,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855568,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3897",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855568,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928032,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928032,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157952,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3723",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157952,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
long int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203808,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3725",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203808,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
long int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228640,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3914",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228640,
      "name": "do_rmdir",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545504,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3988",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545504,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073424,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:4083",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "io_uring/io_uring.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073424,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640048,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:4139",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640048,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857216,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:4218",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857216,
      "name": "do_rmdir",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int do_rmdir(int dfd, struct filename * name)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064208,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:4227",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/init.c:init_rmdir",
        "io_uring/fs.c:io_unlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064208,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493408808,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__arm64_sys_unlinkat",
        "fs/namei.c:__arm64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493408808,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226994420,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:__se_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226994420,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286967728,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:__se_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286967728,
      "name": "do_rmdir",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273119598,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:__se_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273119598,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896768,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896768,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834368,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834368,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888080,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888080,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
long int do_rmdir(int dfd, const char * pathname)
```

```json
{
  "name": "do_rmdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957584,
      "name": "do_rmdir",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957584,
      "name": "do_rmdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
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
