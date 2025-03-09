# Function: <code>do_splice_to</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195136,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:1131",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195136,
      "name": "do_splice_to",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581359168,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:1132",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359168,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438720,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:878",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438720,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493360,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:874",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493360,
      "name": "do_splice_to",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635376,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:858",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635376,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793904,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:859",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793904,
      "name": "do_splice_to",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880960,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:858",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880960,
      "name": "do_splice_to",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005888,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005888,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083840,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083840,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326416,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:853",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326416,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371600,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:771",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371600,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582398912,
      "name": "do_splice_to",
      "external": false,
      "loc": "fs/splice.c:773",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582398912,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720432,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:774",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720432,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265184,
      "name": "do_splice_to",
      "external": false,
      "loc": "fs/splice.c:773",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265184,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847024,
      "name": "do_splice_to",
      "external": false,
      "loc": "fs/splice.c:770",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847024,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493618336,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493618336,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227160560,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227160560,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287206688,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287206688,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273262612,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273262612,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052576,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052576,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990128,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990128,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043856,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043856,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice_to",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115520,
      "name": "do_splice_to",
      "external": true,
      "loc": "fs/splice.c:855",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_direct_to_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115520,
      "name": "do_splice_to",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long int do_splice_to(struct file * in, loff_t * ppos, struct pipe_inode_info * pipe, size_t len, unsigned int flags)
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
