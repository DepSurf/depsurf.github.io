# Function: <code>debugfs_create_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_create_mode(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```

```json
{
  "name": "debugfs_create_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115008,
      "name": "debugfs_create_mode",
      "external": false,
      "loc": "fs/debugfs/file.c:45",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/file.c:debugfs_create_u8",
        "fs/debugfs/file.c:debugfs_create_u16",
        "fs/debugfs/file.c:debugfs_create_u32",
        "fs/debugfs/file.c:debugfs_create_u64",
        "fs/debugfs/file.c:debugfs_create_ulong",
        "fs/debugfs/file.c:debugfs_create_x8",
        "fs/debugfs/file.c:debugfs_create_x16",
        "fs/debugfs/file.c:debugfs_create_x32",
        "fs/debugfs/file.c:debugfs_create_x64",
        "fs/debugfs/file.c:debugfs_create_size_t",
        "fs/debugfs/file.c:debugfs_create_atomic_t",
        "fs/debugfs/file.c:debugfs_create_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115008,
      "name": "debugfs_create_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct dentry * debugfs_create_mode(const char * name, umode_t mode, struct dentry * parent, void * value, const struct file_operations * fops, const struct file_operations * fops_ro, const struct file_operations * fops_wo)
```
</details>
</li>
</ul>
