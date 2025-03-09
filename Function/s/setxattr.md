# Function: <code>setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149936,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:323",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:path_setxattr",
        "fs/xattr.c:SyS_fsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149936,
      "name": "setxattr",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315760,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:334",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315760,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395040,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:439",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395040,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450304,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:439",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450304,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592288,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:440",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592288,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751136,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751136,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837664,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:437",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837664,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962080,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962080,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034832,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034832,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270304,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:508",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270304,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320336,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:546",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320336,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
long int setxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347856,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:567",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347856,
      "name": "setxattr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int setxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666304,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:568",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666304,
      "name": "setxattr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int setxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208848,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:617",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208848,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
long int setxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786320,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:637",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786320,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
long int setxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002656,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:635",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002656,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
long int setxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215296,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:635",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215296,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493559456,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493559456,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227106392,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227106392,
      "name": "setxattr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287132944,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287132944,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273217422,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273217422,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003568,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003568,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941136,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941136,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994848,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994848,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
long int setxattr(struct dentry * d, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065312,
      "name": "setxattr",
      "external": false,
      "loc": "fs/xattr.c:438",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065312,
      "name": "setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
<code>d, name, value, size, flags</code> ➡️ <code>mnt_userns, d, name, value, size, flags</code>
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
