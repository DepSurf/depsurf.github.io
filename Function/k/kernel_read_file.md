# Function: <code>kernel_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176992,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:886",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176992,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581254112,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:891",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254112,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303536,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:917",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303536,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581443728,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443728,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581602304,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:904",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602304,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688960,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:907",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688960,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807088,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807088,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879680,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879680,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105120,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:933",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path_initns",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105120,
      "name": "kernel_read_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071582105472,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407424,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407424,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434624,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434624,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582757392,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757392,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306096,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306096,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
ssize_t kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583891632,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891632,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
ssize_t kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113488,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:init_module_from_file",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113488,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
ssize_t kernel_read_file(struct file * file, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584329840,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/kernel_read_file.c:35",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:init_module_from_file",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/kernel_read_file.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329840,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493352928,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493352928,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226944408,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226944408,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286900496,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286900496,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273079874,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273079874,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848416,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848416,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786080,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786080,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839728,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839728,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909232,
      "name": "kernel_read_file",
      "external": true,
      "loc": "fs/exec.c:908",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/exec.c:kernel_read_file_from_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909232,
      "name": "kernel_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int kernel_read_file(struct file * file, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```
</details>
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
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t * file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t * size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, buf, size, max_size, id</code> ➡️ <code>file, offset, buf, buf_size, file_size, id</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
