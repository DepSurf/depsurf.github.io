# Function: <code>do_sys_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989088,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1015",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_openat",
        "fs/open.c:SyS_creat",
        "fs/compat.c:compat_SyS_open",
        "fs/compat.c:compat_SyS_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989088,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144016,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1026",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_creat",
        "fs/open.c:SyS_openat",
        "fs/compat.c:compat_SyS_openat",
        "fs/compat.c:compat_SyS_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144016,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219200,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1043",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_creat",
        "fs/open.c:SyS_openat",
        "fs/compat.c:compat_SyS_openat",
        "fs/compat.c:compat_SyS_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219200,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266208,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1049",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_creat",
        "fs/open.c:compat_SyS_openat",
        "fs/open.c:compat_SyS_open",
        "fs/open.c:SyS_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266208,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405344,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1049",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_creat",
        "fs/open.c:compat_SyS_openat",
        "fs/open.c:compat_SyS_open",
        "fs/open.c:SyS_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405344,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560064,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1091",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560064,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645216,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1058",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645216,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761952,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1078",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761952,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834160,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834160,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055519,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1193",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": [
        "init/main.c:console_on_rootfs",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057456,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105375,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1186",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107312,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582130319,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1208",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132256,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582446975,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1226",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x64_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x64_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448912,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582965855,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1291",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967440,
      "name": "do_sys_open",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524911,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1323",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526640,
      "name": "do_sys_open",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583740319,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1419",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742016,
      "name": "do_sys_open",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942207,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1416",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943904,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493297472,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__arm64_sys_creat",
        "fs/open.c:__arm64_compat_sys_openat",
        "fs/open.c:__arm64_compat_sys_open",
        "fs/open.c:__arm64_sys_openat",
        "fs/open.c:__arm64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493297472,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226900520,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_creat",
        "fs/open.c:__se_sys_openat",
        "fs/open.c:__se_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226900520,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286836608,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_creat",
        "fs/open.c:__se_compat_sys_openat",
        "fs/open.c:__se_compat_sys_open",
        "fs/open.c:__se_sys_openat",
        "fs/open.c:__se_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286836608,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273042224,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_creat",
        "fs/open.c:__se_sys_openat",
        "fs/open.c:__se_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273042224,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802896,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802896,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740560,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740560,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794208,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794208,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
long int do_sys_open(int dfd, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "do_sys_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863344,
      "name": "do_sys_open",
      "external": true,
      "loc": "fs/open.c:1083",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863344,
      "name": "do_sys_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
