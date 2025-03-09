# Function: <code>fuse_copy_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582057123,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:716",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_read",
        "fs/fuse/dev.c:fuse_dev_splice_read"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271090,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:691",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582360604,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:695",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434240,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:694",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434240,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584736,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:694",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584736,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777360,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:707",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777360,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881776,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:761",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881776,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583060896,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:785",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060896,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167360,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167360,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583505162,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583613818,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:664",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583636605,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:664",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583995757,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:664",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584579351,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:656",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594070319,
      "name": "fuse_copy_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585256519,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:656",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470192,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:658",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470192,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585705216,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:658",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705216,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494880264,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494880264,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228296184,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228296184,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288742080,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288742080,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274210958,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583136096,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136096,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073248,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073248,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120128,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120128,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```

```json
{
  "name": "fuse_copy_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213952,
      "name": "fuse_copy_init",
      "external": false,
      "loc": "fs/fuse/dev.c:651",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213952,
      "name": "fuse_copy_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```
</details>
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
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fuse_copy_init(struct fuse_copy_state * cs, int write, struct iov_iter * iter)
```
</details>
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
