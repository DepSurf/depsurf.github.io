# Function: <code>strndup_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597712,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:155",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_ioctl",
        "fs/namespace.c:SyS_mount",
        "fs/namespace.c:SyS_mount",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597712,
      "name": "strndup_user",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699312,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:155",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_ioctl",
        "fs/namespace.c:SyS_mount",
        "fs/namespace.c:SyS_mount",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699312,
      "name": "strndup_user",
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765120,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:155",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_ioctl",
        "fs/namespace.c:SyS_mount",
        "fs/namespace.c:SyS_mount",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765120,
      "name": "strndup_user",
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801520,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:182",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_ioctl",
        "fs/namespace.c:SyS_mount",
        "fs/namespace.c:SyS_mount",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801520,
      "name": "strndup_user",
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890224,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:182",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_ioctl",
        "fs/namespace.c:SyS_mount",
        "fs/namespace.c:SyS_mount",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890224,
      "name": "strndup_user",
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025952,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:204",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025952,
      "name": "strndup_user",
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103488,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:197",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103488,
      "name": "strndup_user",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168400,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:211",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168400,
      "name": "strndup_user",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226368,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226368,
      "name": "strndup_user",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413856,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413856,
      "name": "strndup_user",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456704,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:219",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456704,
      "name": "strndup_user",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477648,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:219",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477648,
      "name": "strndup_user",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731616,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:219",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731616,
      "name": "strndup_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109776,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:220",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_vma",
        "kernel/module/main.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109776,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583152,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:220",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_vma",
        "kernel/module/main.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583152,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790256,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:243",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_vma",
        "kernel/module/main.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_events_user.c:user_events_ioctl",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790256,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965136,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:243",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_vma",
        "kernel/module/main.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_events_user.c:user_events_ioctl",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/events/core.c:_perf_ioctl",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965136,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492615768,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__arm64_sys_request_key",
        "security/keys/keyctl.c:__arm64_sys_request_key",
        "security/keys/keyctl.c:__arm64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492615768,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226466920,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226466920,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285933008,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285933008,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272641464,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272641464,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195216,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195216,
      "name": "strndup_user",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141968,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141968,
      "name": "strndup_user",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186416,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186416,
      "name": "strndup_user",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
char * strndup_user(const char * s, long int n)
```

```json
{
  "name": "strndup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249664,
      "name": "strndup_user",
      "external": true,
      "loc": "mm/util.c:218",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:ksys_mount",
        "fs/namespace.c:ksys_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_join_session_keyring",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249664,
      "name": "strndup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
