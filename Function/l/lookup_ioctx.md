# Function: <code>lookup_ioctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317712,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1029",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317712,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581484304,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1039",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484304,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565392,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1042",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565392,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620896,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620896,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765568,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1071",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765568,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935776,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1025",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935776,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017952,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1042",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017952,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154640,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154640,
      "name": "lookup_ioctx",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231856,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231856,
      "name": "lookup_ioctx",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469680,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469680,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526896,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1049",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526896,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555680,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1046",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555680,
      "name": "lookup_ioctx",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871808,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x64_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871808,
      "name": "lookup_ioctx",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583435904,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1073",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435904,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025648,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1074",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025648,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584250320,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1071",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250320,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466784,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1081",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466784,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493809112,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493809112,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227315388,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227315388,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287422688,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_compat_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287422688,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273388088,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273388088,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200592,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200592,
      "name": "lookup_ioctx",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138240,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138240,
      "name": "lookup_ioctx",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191072,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191072,
      "name": "lookup_ioctx",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kioctx * lookup_ioctx(long unsigned int ctx_id)
```

```json
{
  "name": "lookup_ioctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267808,
      "name": "lookup_ioctx",
      "external": false,
      "loc": "fs/aio.c:1047",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267808,
      "name": "lookup_ioctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
