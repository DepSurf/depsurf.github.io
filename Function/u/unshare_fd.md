# Function: <code>unshare_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360288,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:1942",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:unshare_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360288,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367440,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2005",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367440,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579385584,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2167",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385584,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373120,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2295",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373120,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399376,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2304",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare",
        "kernel/fork.c:SyS_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399376,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412976,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2379",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412976,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445648,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2487",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445648,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461984,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2778",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461984,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488304,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488304,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532791,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2920",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516384,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579515763,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:2899",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514576,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579518915,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:2931",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517696,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590627,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:3024",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589408,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579682051,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:3101",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680784,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579802595,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:3137",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801264,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850723,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:3373",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849408,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579888531,
      "name": "unshare_fd",
      "external": true,
      "loc": "kernel/fork.c:3363",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887200,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490619696,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490619696,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224700784,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224700784,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283437280,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283437280,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271378918,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271378918,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461968,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461968,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390928,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390928,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461888,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461888,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct * * new_fdp)
```

```json
{
  "name": "unshare_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494304,
      "name": "unshare_fd",
      "external": false,
      "loc": "kernel/fork.c:2795",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494304,
      "name": "unshare_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int max_fds</code>
</li>
<li>
<b>Param reordered. </b>
<code>unshare_flags, new_fdp</code> ➡️ <code>unshare_flags, max_fds, new_fdp</code>
</li>
</ul>
</details>
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
