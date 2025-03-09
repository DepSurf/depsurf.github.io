# Function: <code>kill_ioctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316192,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:799",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:exit_aio",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316192,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483088,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:809",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483088,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564096,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:812",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564096,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621072,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:817",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621072,
      "name": "kill_ioctx",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765744,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:840",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765744,
      "name": "kill_ioctx",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945952,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:803",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945952,
      "name": "kill_ioctx",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032208,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:819",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032208,
      "name": "kill_ioctx",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171056,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071582175372,
      "name": "kill_ioctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248448,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248448,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485808,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485808,
      "name": "kill_ioctx",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542448,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:818",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542448,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572272,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:815",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572272,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889760,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x64_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889760,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583438208,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:842",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438208,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027968,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:846",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027968,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254688,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:844",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254688,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472032,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:854",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472032,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493804552,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__arm64_sys_io_destroy",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493804552,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227315696,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227315696,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287417280,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_compat_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287417280,
      "name": "kill_ioctx",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273393240,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273393240,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217184,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217184,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155024,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155024,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207664,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207664,
      "name": "kill_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int kill_ioctx(struct mm_struct * mm, struct kioctx * ctx, struct ctx_rq_wait * wait)
```

```json
{
  "name": "kill_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267312,
      "name": "kill_ioctx",
      "external": false,
      "loc": "fs/aio.c:816",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:exit_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267312,
      "name": "kill_ioctx",
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
