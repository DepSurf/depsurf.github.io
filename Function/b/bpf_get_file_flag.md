# Function: <code>bpf_get_file_flag</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548668,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546352,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580636431,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:388",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636704,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696844,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:416",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693872,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580769510,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:448",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764032,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819200,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814976,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580936738,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:690",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937040,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933442,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:697",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933744,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950988,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:698",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936448,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581154937,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:714",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140288,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581430542,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:835",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414544,
      "name": "bpf_get_file_flag",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581783094,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:934",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768656,
      "name": "bpf_get_file_flag",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935010,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:933",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930448,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582061634,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:963",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056960,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492144084,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492135600,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226039724,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226034208,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285350508,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285344080,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272305850,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272301266,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788000,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783776,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734176,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729952,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580779248,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775024,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpf_get_file_flag(int flags)
```

```json
{
  "name": "bpf_get_file_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837536,
      "name": "bpf_get_file_flag",
      "external": true,
      "loc": "kernel/bpf/syscall.c:451",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833280,
      "name": "bpf_get_file_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int bpf_get_file_flag(int flags)
```
</details>
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
