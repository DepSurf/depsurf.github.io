# Function: <code>file_open_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984640,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1002",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984640,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139472,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:995",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139472,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214656,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1012",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214656,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261488,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1018",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261488,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400624,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1018",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400624,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555536,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1060",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555536,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641024,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1047",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641024,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757712,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1067",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757712,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829920,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829920,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582050608,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1152",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050608,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100480,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1145",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100480,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124512,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1167",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124512,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
struct file * file_open_root(const struct path * root, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442096,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1185",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442096,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
struct file * file_open_root(const struct path * root, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959040,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1250",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959040,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
struct file * file_open_root(const struct path * root, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517408,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1282",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517408,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
struct file * file_open_root(const struct path * root, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732912,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1379",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732912,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct file * file_open_root(const struct path * root, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933712,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1376",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933712,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493290976,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493290976,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226896328,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:__se_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226896328,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286831072,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286831072,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273038350,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:__se_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273038350,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798656,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798656,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736320,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736320,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789968,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789968,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct file * file_open_root(struct dentry * dentry, struct vfsmount * mnt, const char * filename, int flags, umode_t mode)
```

```json
{
  "name": "file_open_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859104,
      "name": "file_open_root",
      "external": true,
      "loc": "fs/open.c:1072",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859104,
      "name": "file_open_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path * root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount * mnt</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, mnt, filename, flags, mode</code> ➡️ <code>root, filename, flags, mode</code>
</li>
</ul>
</details>
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
