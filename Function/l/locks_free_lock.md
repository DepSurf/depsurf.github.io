# Function: <code>locks_free_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581333536,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:286",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_dispose_list",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:__posix_lock_file",
        "fs/locks.c:__posix_lock_file",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:__break_lease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:SyS_flock",
        "fs/locks.c:fcntl_setlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333536,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513888,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:313",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:SyS_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513888,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599392,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:323",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:SyS_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599392,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660384,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:323",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:SyS_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660384,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806432,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:340",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:SyS_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806432,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980752,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:340",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980752,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068960,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:372",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068960,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582246392,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:379",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230928,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582346216,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330560,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582638300,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619264,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582710380,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691680,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582739708,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721584,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583066620,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048944,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583544645,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:332",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__do_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526544,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145621,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:332",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126688,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584372904,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:333",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584353440,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584591368,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:332",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571776,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493930236,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__arm64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493910328,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227409084,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk64",
        "fs/locks.c:fcntl_getlk64",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__se_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227391028,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287575076,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__se_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287551696,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273481398,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__se_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273466932,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582314952,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299296,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582252712,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237056,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305432,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289776,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void locks_free_lock(struct file_lock * fl)
```

```json
{
  "name": "locks_free_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582384598,
      "name": "locks_free_lock",
      "external": true,
      "loc": "fs/locks.c:380",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlk",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:fcntl_setlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:lease_alloc",
        "fs/locks.c:locks_dispose_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368672,
      "name": "locks_free_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
