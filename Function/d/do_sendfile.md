# Function: <code>do_sendfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995792,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1179",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995792,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581153824,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1324",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153824,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230512,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1353",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230512,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277136,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1364",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277136,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414720,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1367",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile64",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:compat_SyS_sendfile",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile64",
        "fs/read_write.c:SyS_sendfile",
        "fs/read_write.c:SyS_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414720,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571264,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1394",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571264,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656896,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1391",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656896,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774816,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774816,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847040,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847040,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072304,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1503",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072304,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119136,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1188",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119136,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142224,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1186",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142224,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460752,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1177",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_compat_sys_sendfile64",
        "fs/read_write.c:__x64_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x64_compat_sys_sendfile",
        "fs/read_write.c:__x64_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460752,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1123
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978400,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1188",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978400,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1289
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583536240,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1181",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536240,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1289
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751888,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1180",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751888,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954768,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1222",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954768,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1053
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493311824,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_compat_sys_sendfile64",
        "fs/read_write.c:__arm64_compat_sys_sendfile64",
        "fs/read_write.c:__arm64_compat_sys_sendfile",
        "fs/read_write.c:__arm64_compat_sys_sendfile",
        "fs/read_write.c:__arm64_sys_sendfile64",
        "fs/read_write.c:__arm64_sys_sendfile64",
        "fs/read_write.c:__arm64_sys_sendfile",
        "fs/read_write.c:__arm64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493311824,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226912520,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile",
        "fs/read_write.c:__se_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226912520,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286853312,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_compat_sys_sendfile64",
        "fs/read_write.c:__se_compat_sys_sendfile64",
        "fs/read_write.c:__se_compat_sys_sendfile",
        "fs/read_write.c:__se_compat_sys_sendfile",
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile",
        "fs/read_write.c:__se_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286853312,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273050948,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile64",
        "fs/read_write.c:__se_sys_sendfile",
        "fs/read_write.c:__se_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273050948,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815776,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815776,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753440,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753440,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807088,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807088,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t * ppos, size_t count, loff_t max)
```

```json
{
  "name": "do_sendfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876304,
      "name": "do_sendfile",
      "external": false,
      "loc": "fs/read_write.c:1419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__ia32_compat_sys_sendfile64",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__x32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_compat_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__x64_sys_sendfile64",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__ia32_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile",
        "fs/read_write.c:__x64_sys_sendfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876304,
      "name": "do_sendfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
