# Function: <code>vfs_parse_fs_string</code>

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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034240,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034240,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112000,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112000,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348064,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:143",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348064,
      "name": "vfs_parse_fs_string",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399696,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:143",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399696,
      "name": "vfs_parse_fs_string",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426960,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:143",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426960,
      "name": "vfs_parse_fs_string",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582749712,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:166",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582749712,
      "name": "vfs_parse_fs_string",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296544,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:166",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296544,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881312,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:166",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881312,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102960,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:166",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102960,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319104,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:170",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:vfs_parse_monolithic_sep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319104,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493651616,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493651616,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227187432,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227187432,
      "name": "vfs_parse_fs_string",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287246528,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287246528,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273283664,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273283664,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080736,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080736,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018256,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018256,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072016,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072016,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
```

```json
{
  "name": "vfs_parse_fs_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143776,
      "name": "vfs_parse_fs_string",
      "external": true,
      "loc": "fs/fs_context.c:171",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143776,
      "name": "vfs_parse_fs_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_parse_fs_string(struct fs_context * fc, const char * key, const char * value, size_t v_size)
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
