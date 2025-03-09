# Function: <code>umh_pipe_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395632,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:488",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395632,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573664,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:515",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573664,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658544,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:518",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658544,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712864,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:520",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712864,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858528,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:521",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858528,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537760,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:422",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582039296,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:521",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537760,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071582039296,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574352,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:434",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582127456,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:521",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574352,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071582127456,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597792,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289424,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597792,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582289424,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623648,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582388400,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623648,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582388400,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652672,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582674624,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:549",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652672,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582674624,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582743680,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:559",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743680,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772608,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:559",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772608,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583099824,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:559",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099824,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581024,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:493",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581024,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184384,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:499",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184384,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584411920,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:501",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411920,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632656,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:501",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632656,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490789160,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493987408,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490789160,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446603336493987408,
      "name": "umh_pipe_setup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224825496,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227451648,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224825496,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 3227451648,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283614464,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287632640,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283614464,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 13835058055287632640,
      "name": "umh_pipe_setup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271470722,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273505182,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271470722,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446743936273505182,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599952,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582357136,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599952,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582357136,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528592,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582294848,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528592,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582294848,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597232,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582347616,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597232,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582347616,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int umh_pipe_setup(struct subprocess_info * info, struct cred * new)
```

```json
{
  "name": "umh_pipe_setup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630880,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "kernel/umh.c:435",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582427200,
      "name": "umh_pipe_setup",
      "external": false,
      "loc": "fs/coredump.c:547",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630880,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071582427200,
      "name": "umh_pipe_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
