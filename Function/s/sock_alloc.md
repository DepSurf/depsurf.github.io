# Function: <code>sock_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586172480,
      "name": "sock_alloc",
      "external": false,
      "loc": "net/socket.c:536",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_create_lite",
        "net/socket.c:__sock_create",
        "net/socket.c:SYSC_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586172480,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592224,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:536",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592224,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776608,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:562",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776608,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897184,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:560",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897184,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388320,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:566",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388320,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690240,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:563",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690240,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824304,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:542",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824304,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588127040,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127040,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588331808,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331808,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589192576,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:568",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192576,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191136,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:569",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191136,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589084656,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:571",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084656,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589802352,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:621",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589802352,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591320336,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:622",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320336,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074176,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:624",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074176,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593525488,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:627",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593525488,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594296720,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:629",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594296720,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501826072,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501826072,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234608472,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234608472,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295227584,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295227584,
      "name": "sock_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278172288,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278172288,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587938592,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938592,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651696,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651696,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270368,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270368,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct socket * sock_alloc()
```

```json
{
  "name": "sock_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588405648,
      "name": "sock_alloc",
      "external": true,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588405648,
      "name": "sock_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
