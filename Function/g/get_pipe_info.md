# Function: <code>get_pipe_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581032528,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1080",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032528,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581191901,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1098",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191840,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269053,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1141",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268992,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581318045,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1140",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317984,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581458301,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1147",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458240,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581617829,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1138",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617792,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704053,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1131",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704016,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581821957,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821920,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581894517,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894480,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124501,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1350",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124432,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170965,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1349",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170896,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582195605,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1363",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195536,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582512933,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1366",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512864,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037573,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1372",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037488,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583602309,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1372",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602208,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583819189,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1377",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819088,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct pipe_inode_info * get_pipe_info(struct file * file, bool for_splice)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584025173,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1394",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "kernel/watch_queue.c:get_watch_queue",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025072,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493373420,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493373304,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226960044,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226959976,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286921304,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286921216,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273091772,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273091686,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581863253,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863216,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581800853,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800816,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854565,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854528,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct pipe_inode_info * get_pipe_info(struct file * file)
```

```json
{
  "name": "get_pipe_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924053,
      "name": "get_pipe_info",
      "external": true,
      "loc": "fs/pipe.c:1143",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924016,
      "name": "get_pipe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_splice</code>
</li>
</ul>
</details>
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
