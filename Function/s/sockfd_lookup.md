# Function: <code>sockfd_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586171424,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:431",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171424,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592144,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:431",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592144,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776528,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:473",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776528,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897104,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:471",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897104,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388240,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:477",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:sock_map_update_elem",
        "net/compat.c:compat_SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388240,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690160,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:471",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/sockmap.c:sock_hash_update_elem",
        "kernel/bpf/sockmap.c:sock_map_update_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690160,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824224,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:450",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824224,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588126960,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588126960,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588331728,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331728,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589192480,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:476",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192480,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191040,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:474",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191040,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589084560,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:475",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084560,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589802256,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:525",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589802256,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591320224,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:526",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320224,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074048,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:528",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074048,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593525360,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:531",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/handshake/netlink.c:handshake_nl_done_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593525360,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594296592,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:533",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/handshake/netlink.c:handshake_nl_done_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594296592,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501825936,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501825936,
      "name": "sockfd_lookup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234608360,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234608360,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295227408,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295227408,
      "name": "sockfd_lookup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278172176,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278172176,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587938512,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938512,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651616,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651616,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270288,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270288,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct socket * sockfd_lookup(int fd, int * err)
```

```json
{
  "name": "sockfd_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588405568,
      "name": "sockfd_lookup",
      "external": true,
      "loc": "net/socket.c:461",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588405568,
      "name": "sockfd_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
