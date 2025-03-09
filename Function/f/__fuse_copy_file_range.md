# Function: <code>__fuse_copy_file_range</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107904,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3115",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107904,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213392,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213392,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541408,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3274",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541408,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583651104,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3333",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651104,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671680,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:2987",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671680,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030704,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3022",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030704,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618848,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3047",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618848,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298400,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3082",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298400,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528752,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3059",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528752,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585765904,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3082",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585765904,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494933784,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494933784,
      "name": "__fuse_copy_file_range",
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228343920,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228343920,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288805552,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288805552,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274240224,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274240224,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182128,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182128,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583119280,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119280,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166160,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166160,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259728,
      "name": "__fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3249",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259728,
      "name": "__fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ssize_t __fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```
</details>
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
