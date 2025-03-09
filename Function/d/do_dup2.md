# Function: <code>do_dup2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114176,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:817",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:SyS_dup2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114176,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279920,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:823",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279920,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358368,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:823",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358368,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413472,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:809",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413472,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555088,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:812",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555088,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711392,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711392,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798048,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:838",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798048,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916880,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916880,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989264,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989264,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223008,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:869",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223008,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270752,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1005",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270752,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296256,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1017",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296256,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615152,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1077",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615152,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149504,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1079",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149504,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723456,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1089",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723456,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940512,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1104",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940512,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145856,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:1233",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145856,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493502280,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493502280,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227060792,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227060792,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287065568,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287065568,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273175684,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273175684,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958000,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958000,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895568,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895568,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949312,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949312,
      "name": "do_dup2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int do_dup2(struct files_struct * files, struct file * file, unsigned int fd, unsigned int flags)
```

```json
{
  "name": "do_dup2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019232,
      "name": "do_dup2",
      "external": false,
      "loc": "fs/file.c:844",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019232,
      "name": "do_dup2",
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
