# Function: <code>path_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150464,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:372",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_setxattr",
        "fs/xattr.c:SyS_lsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150464,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316144,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:375",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lsetxattr",
        "fs/xattr.c:SyS_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316144,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395424,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:480",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lsetxattr",
        "fs/xattr.c:SyS_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395424,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450752,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:483",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lsetxattr",
        "fs/xattr.c:SyS_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450752,
      "name": "path_setxattr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592736,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:484",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lsetxattr",
        "fs/xattr.c:SyS_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592736,
      "name": "path_setxattr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751632,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751632,
      "name": "path_setxattr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838160,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:481",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838160,
      "name": "path_setxattr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962704,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962704,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035456,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035456,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270928,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:552",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270928,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320832,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:584",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320832,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348384,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:606",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348384,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666832,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:607",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666832,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209072,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:641",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209072,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786560,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:661",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786560,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002896,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:659",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002896,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215536,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:659",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215536,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493560368,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_lsetxattr",
        "fs/xattr.c:__arm64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493560368,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227106908,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lsetxattr",
        "fs/xattr.c:__se_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227106908,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287133840,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lsetxattr",
        "fs/xattr.c:__se_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287133840,
      "name": "path_setxattr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273217854,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lsetxattr",
        "fs/xattr.c:__se_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273217854,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004192,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004192,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941760,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941760,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995472,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995472,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int path_setxattr(const char * pathname, const char * name, const void * value, size_t size, int flags, unsigned int lookup_flags)
```

```json
{
  "name": "path_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065936,
      "name": "path_setxattr",
      "external": false,
      "loc": "fs/xattr.c:482",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lsetxattr",
        "fs/xattr.c:__x64_sys_lsetxattr",
        "fs/xattr.c:__ia32_sys_setxattr",
        "fs/xattr.c:__x64_sys_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065936,
      "name": "path_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
