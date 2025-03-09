# Function: <code>debugfs_create_mode_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332480,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:316",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332480,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423280,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:313",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423280,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582506848,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:313",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582506848,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657488,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:355",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657488,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850992,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:376",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850992,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959280,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:378",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959280,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140064,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:378",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140064,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246240,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246240,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583576250,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:392",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583696714,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:392",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583722378,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:392",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584083178,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:396",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584676937,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:396",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585361753,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:412",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585590965,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:412",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585831349,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:504",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_create_str",
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494971808,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494971808,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228378264,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228378264,
      "name": "debugfs_create_mode_unsafe",
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288851776,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288851776,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274272612,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274272612,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214976,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214976,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152128,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152128,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583199008,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199008,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode_unsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292896,
      "name": "debugfs_create_mode_unsafe",
      "external": false,
      "loc": "fs/debugfs/file.c:381",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_bool",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292896,
      "name": "debugfs_create_mode_unsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct dentry * debugfs_create_mode_unsafe(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
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
