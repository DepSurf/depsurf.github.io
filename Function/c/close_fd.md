# Function: <code>close_fd</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582275720,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:619",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270528,
      "name": "close_fd",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301224,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:619",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296032,
      "name": "close_fd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582620264,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:633",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_close",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614928,
      "name": "close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583155333,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:653",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_close",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148688,
      "name": "close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583729061,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:653",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_close",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722720,
      "name": "close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583946133,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:654",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_close",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939776,
      "name": "close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int close_fd(unsigned int fd)
```

```json
{
  "name": "close_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584153781,
      "name": "close_fd",
      "external": true,
      "loc": "fs/file.c:661",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:replace_fd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_close",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151200,
      "name": "close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int close_fd(unsigned int fd)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
