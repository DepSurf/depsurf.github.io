# Function: <code>fuse_copy_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049968,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:976",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_args",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049968,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263840,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:951",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263840,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1699
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353488,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:954",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353488,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437552,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:953",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437552,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1587
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587920,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:953",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587920,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1699
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:966",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780480,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1559
    },
    {
      "addr": 18446744071582793971,
      "name": "fuse_copy_page.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:1020",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883744,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1561
    },
    {
      "addr": 18446744071582898387,
      "name": "fuse_copy_page.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583064368,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:1044",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064368,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173776,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173776,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583497472,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:909",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497472,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583606176,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:930",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606176,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629424,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:927",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629424,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988480,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:933",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988480,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571520,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:925",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571520,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585247616,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:926",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247616,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585477360,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:928",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585477360,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712384,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:928",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712384,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494889280,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494889280,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228303320,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228303320,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288751568,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288751568,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274204388,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274204388,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583142512,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142512,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079664,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079664,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126544,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126544,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int fuse_copy_page(struct fuse_copy_state * cs, struct page * * pagep, unsigned int offset, unsigned int count, int zeroing)
```

```json
{
  "name": "fuse_copy_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220096,
      "name": "fuse_copy_page",
      "external": false,
      "loc": "fs/fuse/dev.c:910",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_copy_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220096,
      "name": "fuse_copy_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
