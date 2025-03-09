# Function: <code>__sock_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:593",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689312,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071587710074,
      "name": "__sock_release.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:572",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821600,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071587843402,
      "name": "__sock_release.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124800,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071588147468,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329568,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071588352732,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589202277,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:598",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190224,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071589212654,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589200309,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:590",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188672,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071591625524,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589093909,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:592",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082768,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071591568914,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589809637,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:642",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801760,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071592692090,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591328533,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:643",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591319680,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071594577574,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593073408,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:645",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593073408,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593524704,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:648",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593524704,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594295936,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:650",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594295936,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501825032,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501825032,
      "name": "__sock_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234607556,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234607556,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295225600,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295225600,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278170464,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278170464,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936352,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071587959516,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649456,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071587672620,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268128,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071588291292,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```

```json
{
  "name": "__sock_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_release",
      "external": false,
      "loc": "net/socket.c:583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403408,
      "name": "__sock_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071588426392,
      "name": "__sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __sock_release(struct socket * sock, struct inode * inode)
```
</details>
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
