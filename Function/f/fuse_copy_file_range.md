# Function: <code>fuse_copy_file_range</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929088,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3029",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929088,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108752,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3205",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108752,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214240,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214240,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583542320,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3382",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542320,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583652032,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3442",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652032,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672608,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3096",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672608,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031600,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3133",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031600,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619744,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3154",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619744,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585299312,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3189",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299312,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529680,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3166",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529680,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766832,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3189",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766832,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494934472,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494934472,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228344696,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228344696,
      "name": "fuse_copy_file_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288806432,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288806432,
      "name": "fuse_copy_file_range",
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274240830,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274240830,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182976,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182976,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120128,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120128,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167008,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167008,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
ssize_t fuse_copy_file_range(struct file * src_file, loff_t src_off, struct file * dst_file, loff_t dst_off, size_t len, unsigned int flags)
```

```json
{
  "name": "fuse_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260576,
      "name": "fuse_copy_file_range",
      "external": false,
      "loc": "fs/fuse/file.c:3339",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260576,
      "name": "fuse_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
ssize_t fuse_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * src_file</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t src_off</code>
</li>
<li>
<b>Param added. </b>
<code>struct file * dst_file</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t dst_off</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file_in</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t pos_in</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file_out</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t pos_out</code>
</li>
</ul>
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
