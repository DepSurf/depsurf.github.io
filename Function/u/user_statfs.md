# Function: <code>user_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211392,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:77",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_statfs",
        "fs/statfs.c:SYSC_statfs64",
        "fs/compat.c:C_SYSC_statfs",
        "fs/compat.c:C_SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211392,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376080,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:77",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_statfs64",
        "fs/statfs.c:SYSC_statfs",
        "fs/compat.c:C_SYSC_statfs64",
        "fs/compat.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376080,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453824,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:77",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_statfs64",
        "fs/statfs.c:SYSC_statfs",
        "fs/compat.c:C_SYSC_statfs64",
        "fs/compat.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453824,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509344,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:80",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_statfs64",
        "fs/statfs.c:C_SYSC_statfs",
        "fs/statfs.c:SYSC_statfs64",
        "fs/statfs.c:SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509344,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651968,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:81",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_statfs64",
        "fs/statfs.c:C_SYSC_statfs",
        "fs/statfs.c:SYSC_statfs64",
        "fs/statfs.c:SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651968,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814848,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:81",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814848,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901840,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:81",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901840,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027376,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027376,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105312,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105312,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342112,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342112,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582393632,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582393632,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420928,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420928,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582743744,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743744,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290496,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290496,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874240,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874240,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096000,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096000,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312144,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:97",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312144,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493643896,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493643896,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227180512,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_sys_statfs64",
        "fs/statfs.c:__se_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227180512,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287235184,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287235184,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273277546,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273277546,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074048,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074048,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582011600,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011600,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065328,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065328,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int user_statfs(const char * pathname, struct kstatfs * st)
```

```json
{
  "name": "user_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137072,
      "name": "user_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_statfs64",
        "fs/statfs.c:__do_compat_sys_statfs",
        "fs/statfs.c:__do_sys_statfs64",
        "fs/statfs.c:__do_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137072,
      "name": "user_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
