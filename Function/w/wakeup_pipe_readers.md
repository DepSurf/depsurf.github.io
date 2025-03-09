# Function: <code>wakeup_pipe_readers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194128,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194128,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358160,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_to_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358160,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438496,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:164",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438496,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493136,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:166",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493136,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635152,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:166",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635152,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793680,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:166",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793680,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880736,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:166",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880736,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005664,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005664,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083616,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083616,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582322965,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:164",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582376837,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408125,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582729901,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583275698,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583858146,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:163",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584079304,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:181",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584295491,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:178",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493618088,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493618088,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227160328,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227160328,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287206352,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287206352,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273262420,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273262420,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052352,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052352,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989904,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989904,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043632,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043632,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```

```json
{
  "name": "wakeup_pipe_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115328,
      "name": "wakeup_pipe_readers",
      "external": false,
      "loc": "fs/splice.c:165",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115328,
      "name": "wakeup_pipe_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info * pipe)
```
</details>
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
