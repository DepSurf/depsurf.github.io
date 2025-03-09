# Function: <code>path_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147776,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:625",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_removexattr",
        "fs/xattr.c:SyS_lremovexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147776,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314960,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:617",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lremovexattr",
        "fs/xattr.c:SyS_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314960,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394224,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:722",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lremovexattr",
        "fs/xattr.c:SyS_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394224,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449520,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:719",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lremovexattr",
        "fs/xattr.c:SyS_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449520,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591504,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:720",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lremovexattr",
        "fs/xattr.c:SyS_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591504,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749888,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749888,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836416,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:717",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836416,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960800,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960800,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033552,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033552,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267024,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:788",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267024,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316576,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:820",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316576,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344000,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:848",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344000,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582664816,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:849",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664816,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205552,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:901",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205552,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583784640,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:924",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784640,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999728,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:921",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999728,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212368,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:921",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212368,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493555952,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_lremovexattr",
        "fs/xattr.c:__arm64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493555952,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227105572,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lremovexattr",
        "fs/xattr.c:__se_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227105572,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287131104,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lremovexattr",
        "fs/xattr.c:__se_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287131104,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273216750,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lremovexattr",
        "fs/xattr.c:__se_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273216750,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002288,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002288,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939856,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939856,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993568,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993568,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int path_removexattr(const char * pathname, const char * name, unsigned int lookup_flags)
```

```json
{
  "name": "path_removexattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064032,
      "name": "path_removexattr",
      "external": false,
      "loc": "fs/xattr.c:718",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lremovexattr",
        "fs/xattr.c:__x64_sys_lremovexattr",
        "fs/xattr.c:__ia32_sys_removexattr",
        "fs/xattr.c:__x64_sys_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064032,
      "name": "path_removexattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
