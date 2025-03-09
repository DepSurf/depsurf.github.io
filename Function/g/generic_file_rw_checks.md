# Function: <code>generic_file_rw_checks</code>

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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048064,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3093",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048064,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103728,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103728,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286160,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3059",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286160,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123728,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1671",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123728,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148624,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1676",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148624,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465456,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1667",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465456,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985312,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1698",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985312,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545600,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545600,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761552,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1703",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761552,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964240,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "fs/read_write.c:1720",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964240,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492467352,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492467352,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226345140,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226345140,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285751424,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285751424,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272538818,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272538818,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072576,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072576,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019760,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019760,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063776,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063776,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
```

```json
{
  "name": "generic_file_rw_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125328,
      "name": "generic_file_rw_checks",
      "external": true,
      "loc": "mm/filemap.c:3050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_copy_file_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125328,
      "name": "generic_file_rw_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int generic_file_rw_checks(struct file * file_in, struct file * file_out)
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
