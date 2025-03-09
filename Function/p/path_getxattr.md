# Function: <code>path_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149168,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:481",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_getxattr",
        "fs/xattr.c:SyS_lgetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149168,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314336,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:476",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lgetxattr",
        "fs/xattr.c:SyS_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314336,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393632,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:581",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lgetxattr",
        "fs/xattr.c:SyS_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393632,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448448,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:581",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lgetxattr",
        "fs/xattr.c:SyS_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448448,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590432,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:582",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:SyS_lgetxattr",
        "fs/xattr.c:SyS_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590432,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747952,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747952,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834480,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:579",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834480,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958880,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958880,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031632,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031632,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269600,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:650",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269600,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319632,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:682",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319632,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347120,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:708",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347120,
      "name": "path_getxattr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669360,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:709",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669360,
      "name": "path_getxattr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210752,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:761",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210752,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788384,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:781",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788384,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004720,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:778",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004720,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217360,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:778",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217360,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493557408,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__arm64_sys_lgetxattr",
        "fs/xattr.c:__arm64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493557408,
      "name": "path_getxattr",
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227104028,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lgetxattr",
        "fs/xattr.c:__se_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227104028,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287128752,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lgetxattr",
        "fs/xattr.c:__se_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287128752,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273215814,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__se_sys_lgetxattr",
        "fs/xattr.c:__se_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273215814,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000368,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000368,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937936,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937936,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991648,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991648,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ssize_t path_getxattr(const char * pathname, const char * name, void * value, size_t size, unsigned int lookup_flags)
```

```json
{
  "name": "path_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062112,
      "name": "path_getxattr",
      "external": false,
      "loc": "fs/xattr.c:580",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__ia32_sys_lgetxattr",
        "fs/xattr.c:__x64_sys_lgetxattr",
        "fs/xattr.c:__ia32_sys_getxattr",
        "fs/xattr.c:__x64_sys_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062112,
      "name": "path_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
