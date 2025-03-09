# Function: <code>getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581148576,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:431",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:SyS_fgetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148576,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581313872,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:434",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313872,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393168,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:539",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393168,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448000,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:542",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448000,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589984,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:543",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589984,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747504,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747504,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834032,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:540",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834032,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958304,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958304,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031040,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031040,
      "name": "getxattr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269008,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:611",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269008,
      "name": "getxattr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319040,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:643",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319040,
      "name": "getxattr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582346512,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:669",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582346512,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
ssize_t getxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668752,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:670",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668752,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
ssize_t getxattr(struct user_namespace * mnt_userns, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210512,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:736",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210512,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
ssize_t getxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788128,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:756",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788128,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
ssize_t getxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004464,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:753",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004464,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
ssize_t getxattr(struct mnt_idmap * idmap, struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217104,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:753",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217104,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493556704,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493556704,
      "name": "getxattr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227103572,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227103572,
      "name": "getxattr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287128016,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287128016,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273215466,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273215466,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999776,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999776,
      "name": "getxattr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937344,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937344,
      "name": "getxattr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991056,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991056,
      "name": "getxattr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry * d, const char * name, void * value, size_t size)
```

```json
{
  "name": "getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061520,
      "name": "getxattr",
      "external": false,
      "loc": "fs/xattr.c:541",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061520,
      "name": "getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
<code>d, name, value, size</code> ➡️ <code>mnt_userns, d, name, value, size</code>
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
