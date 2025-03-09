# Function: <code>sock_from_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586166400,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:408",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup",
        "net/socket.c:sockfd_lookup_light"
      ],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166400,
      "name": "sock_from_file",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586594635,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:408",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586848,
      "name": "sock_from_file",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586779003,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:450",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771184,
      "name": "sock_from_file",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586900123,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:448",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "net/core/scm.c:scm_detach_fds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894064,
      "name": "sock_from_file",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587391867,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:454",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "net/core/scm.c:scm_detach_fds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385584,
      "name": "sock_from_file",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587692526,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:448",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688688,
      "name": "sock_from_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826622,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:427",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820960,
      "name": "sock_from_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588129483,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124192,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588334619,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328992,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589204837,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:453",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "net/core/sock.c:__receive_sock",
        "net/core/scm.c:__scm_install_fd",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189648,
      "name": "sock_from_file",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589202869,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:452",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188112,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589096437,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:453",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082208,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589814085,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:503",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:do_accept",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801232,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591333845,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:504",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:do_accept",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:io_send",
        "io_uring/io_uring.c:io_sendmsg",
        "io_uring/io_uring.c:io_shutdown",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591318800,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593088837,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:506",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:do_accept",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_shutdown",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593072480,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593540981,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:509",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:do_accept",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/splice.c:splice_to_socket",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_shutdown",
        "io_uring/net.c:io_shutdown",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593523760,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594313637,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:511",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_connect_file",
        "net/socket.c:do_accept",
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/splice.c:splice_to_socket",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_shutdown",
        "io_uring/net.c:io_shutdown",
        "net/core/sock.c:__receive_sock",
        "net/core/filter.c:bpf_sock_from_file",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594295056,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501828404,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501823992,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234610044,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234606756,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295230628,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295224080,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278174760,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278169616,
      "name": "sock_from_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587941403,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935776,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587654507,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648880,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588273179,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588267552,
      "name": "sock_from_file",
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
struct socket * sock_from_file(struct file * file, int * err)
```

```json
{
  "name": "sock_from_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588408491,
      "name": "sock_from_file",
      "external": true,
      "loc": "net/socket.c:438",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:sockfd_lookup_light",
        "net/socket.c:sockfd_lookup"
      ],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/io_uring.c:io_send_recvmsg",
        "net/core/scm.c:scm_detach_fds",
        "net/core/netprio_cgroup.c:update_netprio",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402720,
      "name": "sock_from_file",
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * err</code>
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
