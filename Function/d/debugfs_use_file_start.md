# Function: <code>debugfs_use_file_start</code>

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
int debugfs_use_file_start(const struct dentry * dentry, int * srcu_idx)
```

```json
{
  "name": "debugfs_use_file_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582333515,
      "name": "debugfs_use_file_start",
      "external": true,
      "loc": "fs/debugfs/file.c:72",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329920,
      "name": "debugfs_use_file_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int debugfs_use_file_start(const struct dentry * dentry, int * srcu_idx)
```

```json
{
  "name": "debugfs_use_file_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424315,
      "name": "debugfs_use_file_start",
      "external": true,
      "loc": "fs/debugfs/file.c:72",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420720,
      "name": "debugfs_use_file_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int debugfs_use_file_start(const struct dentry * dentry, int * srcu_idx)
```

```json
{
  "name": "debugfs_use_file_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582507879,
      "name": "debugfs_use_file_start",
      "external": true,
      "loc": "fs/debugfs/file.c:72",
      "file": "fs/debugfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504320,
      "name": "debugfs_use_file_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int debugfs_use_file_start(const struct dentry * dentry, int * srcu_idx)
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int debugfs_use_file_start(const struct dentry * dentry, int * srcu_idx)
```
</details>
</li>
</ul>
