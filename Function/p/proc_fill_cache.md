# Function: <code>proc_fill_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457904,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1801",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457904,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642160,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1817",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642160,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730432,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1837",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730432,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784560,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1878",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784560,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934112,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1879",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934112,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118000,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1855",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118000,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212512,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1869",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212512,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582376560,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582376560,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475472,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475472,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582773744,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2015",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773744,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846976,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2029",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846976,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875392,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2028",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875392,
      "name": "proc_fill_cache",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209024,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2034",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209024,
      "name": "proc_fill_cache",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583705712,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2063",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705712,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316496,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2064",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316496,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546384,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2064",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546384,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778208,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:2058",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778208,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494095024,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494095024,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227546220,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227546220,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287762384,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287762384,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273582362,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273582362,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582444208,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444208,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381376,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381376,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434688,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434688,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
bool proc_fill_cache(struct file * file, struct dir_context * ctx, const char * name, unsigned int len, instantiate_t * instantiate, struct task_struct * task, const void * ptr)
```

```json
{
  "name": "proc_fill_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514784,
      "name": "proc_fill_cache",
      "external": true,
      "loc": "fs/proc/base.c:1882",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514784,
      "name": "proc_fill_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>unsigned int len</code>
</li>
</ul>
</details>
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
