# Function: <code>sock_update_netprioidx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_update_netprioidx(struct sock * sk)
```

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586190320,
      "name": "sock_update_netprioidx",
      "external": true,
      "loc": "net/core/sock.c:1396",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193600,
      "name": "sock_update_netprioidx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586608761,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586669562,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586793089,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586854522,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586924735,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586977722,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587416863,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587475914,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587722854,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781054,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587855030,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913953,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:40",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588159449,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222343,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588364713,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426967,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589234027,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589292736,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:__scm_install_fd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589233135,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589126943,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589846015,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591372015,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593125503,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593578127,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594350623,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:__receive_sock",
        "net/core/sock.c:sk_alloc",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501866880,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501945796,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234634816,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234701564,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295277436,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295367600,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278195058,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278250436,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587971497,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588033751,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587684601,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587746839,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588303273,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365527,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_update_netprioidx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588438608,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500977,
      "name": "sock_update_netprioidx",
      "external": false,
      "loc": "include/net/netprio_cgroup.h:34",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void sock_update_netprioidx(struct sock * sk)
```
</details>
</li>
</ul>
