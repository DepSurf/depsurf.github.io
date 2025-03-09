# Function: <code>kernel_read_file_from_fd</code>

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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177632,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:977",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177632,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254752,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:982",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254752,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304176,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:1008",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304176,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444320,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:989",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444320,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602848,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:993",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602848,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689536,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:996",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689536,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807648,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807648,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880240,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880240,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105696,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:1048",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105696,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408224,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408224,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435424,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435424,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758192,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758192,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307344,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307344,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892976,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892976,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114848,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114848,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
ssize_t kernel_read_file_from_fd(int fd, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331200,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/kernel_read_file.c:174",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_prepare_segments",
        "kernel/kexec_file.c:kimage_file_prepare_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331200,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493353608,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493353608,
      "name": "kernel_read_file_from_fd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226945208,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__se_sys_finit_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226945208,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286901488,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286901488,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273080354,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273080354,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848976,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848976,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786640,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786640,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840288,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840288,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909792,
      "name": "kernel_read_file_from_fd",
      "external": true,
      "loc": "fs/exec.c:997",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909792,
      "name": "kernel_read_file_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_read_file_from_fd(int fd, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t * file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t * size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>fd, buf, size, max_size, id</code> ➡️ <code>fd, offset, buf, buf_size, file_size, id</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
