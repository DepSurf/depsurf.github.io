# Function: <code>ext4_datasem_ensure_credits</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582908080,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:117",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908080,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979952,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:117",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979952,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005680,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:117",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005680,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342800,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:117",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342800,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852576,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:117",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852576,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476688,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:136",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476688,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705488,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:136",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705488,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```

```json
{
  "name": "ext4_datasem_ensure_credits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584938112,
      "name": "ext4_datasem_ensure_credits",
      "external": true,
      "loc": "fs/ext4/extents.c:136",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584938112,
      "name": "ext4_datasem_ensure_credits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_datasem_ensure_credits(handle_t * handle, struct inode * inode, int check_cred, int restart_cred, int revoke_cred)
```
</details>
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
