# Function: <code>compat_get_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965200,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:890",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "mm/mempolicy.c:compat_SyS_set_mempolicy",
        "mm/mempolicy.c:compat_SyS_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965200,
      "name": "compat_get_bitmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995744,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:890",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "mm/mempolicy.c:compat_SyS_mbind",
        "mm/mempolicy.c:compat_SyS_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995744,
      "name": "compat_get_bitmap",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026240,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:898",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026240,
      "name": "compat_get_bitmap",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028528,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:453",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028528,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075232,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:412",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075232,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134624,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:377",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134624,
      "name": "compat_get_bitmap",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181840,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:348",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181840,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227248,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227248,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275456,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275456,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343616,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343616,
      "name": "compat_get_bitmap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328752,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328752,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331984,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331984,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486608,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:get_bitmap",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486608,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681280,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:get_nodes",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681280,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952576,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:get_nodes",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952576,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039568,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:get_nodes",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "io_uring/io_uring.c:io_register_iowq_aff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039568,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136784,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:193",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:get_nodes",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "io_uring/register.c:io_register_iowq_aff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136784,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491520912,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__arm64_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_mbind",
        "mm/mempolicy.c:__arm64_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491520912,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284486432,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__do_compat_sys_sched_setaffinity",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_mbind",
        "mm/mempolicy.c:__se_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284486432,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244256,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244256,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191808,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191808,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235504,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235504,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```

```json
{
  "name": "compat_get_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288496,
      "name": "compat_get_bitmap",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_get_user_cpu_mask",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "fs/select.c:compat_get_fd_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288496,
      "name": "compat_get_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int compat_get_bitmap(long unsigned int * mask, const compat_ulong_t * umask, long unsigned int bitmap_size)
```
</details>
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
