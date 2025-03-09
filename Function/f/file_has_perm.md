# Function: <code>file_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263408,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1704",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263408,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481392,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1777",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481392,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574304,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1785",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574304,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665344,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1774",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665344,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834128,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1782",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834128,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020176,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1884",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020176,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583136064,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1698",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136064,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323520,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1742",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323520,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428880,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428880,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768848,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1697",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768848,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888528,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1706",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888528,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583914944,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1765",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914944,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278272,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1757",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278272,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584886880,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1695",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584886880,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585593664,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1694",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585593664,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824416,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1705",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824416,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072848,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1745",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072848,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495186608,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495186608,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228575068,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228575068,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289129984,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289129984,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274426222,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274426222,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397616,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397616,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334688,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334688,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381392,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381392,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int file_has_perm(const struct cred * cred, struct file * file, u32 av)
```

```json
{
  "name": "file_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478416,
      "name": "file_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1744",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_file_receive",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_fcntl",
        "security/selinux/hooks.c:selinux_file_lock",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:file_map_prot_check",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478416,
      "name": "file_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
