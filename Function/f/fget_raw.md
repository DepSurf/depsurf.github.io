# Function: <code>fget_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581113552,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:722",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113552,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284070,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:723",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279280,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581362486,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:723",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357728,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417782,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:709",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412896,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581559350,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:712",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554512,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715365,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:708",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710544,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802085,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/events/core.c:perf_event_get",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797056,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581920917,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915888,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581993301,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988272,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227317,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:757",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222496,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272661,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:857",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270016,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582297689,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:869",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295520,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582616505,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:929",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614400,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149344,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:931",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149344,
      "name": "fget_raw",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722144,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:931",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722144,
      "name": "fget_raw",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939184,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:932",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939184,
      "name": "fget_raw",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584148907,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:1054",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148416,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493508840,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493502000,
      "name": "fget_raw",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227065316,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227060572,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287072772,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287063648,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273180996,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273174144,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581962037,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957008,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899605,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894576,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581953349,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948320,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct file * fget_raw(unsigned int fd)
```

```json
{
  "name": "fget_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023605,
      "name": "fget_raw",
      "external": true,
      "loc": "fs/file.c:744",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020464,
      "name": "fget_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
