# Function: <code>removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147648,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:611",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:SyS_fremovexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147648,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314832,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:603",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314832,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394096,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:708",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394096,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449392,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:705",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449392,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591376,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:706",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591376,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749760,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749760,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836288,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:703",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836288,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960672,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960672,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033424,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033424,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266896,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:774",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266896,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316448,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:806",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316448,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
long int removexattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582343856,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:833",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343856,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long int removexattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582664672,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:834",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664672,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long int removexattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205392,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:886",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205392,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
long int removexattr(struct mnt_idmap * idmap, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583784272,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:906",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784272,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
long int removexattr(struct mnt_idmap * idmap, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999392,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:903",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999392,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
long int removexattr(struct mnt_idmap * idmap, struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212032,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:903",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212032,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493555808,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493555808,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227105444,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227105444,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287130944,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287130944,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273216660,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273216660,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002160,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002160,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939728,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939728,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993440,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993440,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int removexattr(struct dentry * d, const char * name)
```

```json
{
  "name": "removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063904,
      "name": "removexattr",
      "external": false,
      "loc": "fs/xattr.c:704",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063904,
      "name": "removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>d, name</code> ➡️ <code>mnt_userns, d, name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
