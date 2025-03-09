# Function: <code>sock_reset_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586167292,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:756",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195885,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:756",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586611677,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:756",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586622014,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:756",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586675452,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:756",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587740,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621797,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587039953,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587056316,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085614,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121952,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:758",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586772108,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586806405,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587236177,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587252175,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282398,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319664,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:779",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586894860,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928238,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587366182,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587383880,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397438,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587451350,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587386268,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587420932,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587886310,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915814,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587918931,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587972721,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:793",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587689293,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587724975,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588232985,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588264215,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588283134,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322449,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:800",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586578132,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587821581,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587857295,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588420153,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452471,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588456206,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588511551,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:828",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586829916,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588124777,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588161824,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824047,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858221,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862334,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588910778,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586975996,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588329545,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367088,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589047199,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081821,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086510,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589134522,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587802380,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589190201,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228648,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590007860,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590046088,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590064750,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590105350,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591090205,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:878",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587858866,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589188649,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589226654,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506620,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050356,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590087624,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590152283,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591167958,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587737845,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082748,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589119654,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589404753,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589965124,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590002296,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590065552,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591101834,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591149802,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:884",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588333060,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589801740,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589838117,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171514,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590732212,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590772877,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590839202,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591945284,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592000650,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:896",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589724664,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591319449,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591361408,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591734412,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592362702,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592405533,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592474921,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593670741,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593735038,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:936",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591346584,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593078361,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593118157,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594208841,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594253445,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594330569,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595601859,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595674295,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:974",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_reset_flag(struct sock * sk, enum sock_flags flag)
```

```json
{
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591708339,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593529942,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593570857,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071594595875,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594640179,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594718002,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596110415,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596184588,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:976",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593553344,
      "name": "sock_reset_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_reset_flag(struct sock * sk, enum sock_flags flag)
```

```json
{
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592452003,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594301782,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594343449,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071595399561,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595443489,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595521981,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596982498,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597060115,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:947",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594325680,
      "name": "sock_reset_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501825008,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501876836,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502658884,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502697952,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502701908,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502748956,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232507956,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234607348,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 3234640880,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235362412,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235399368,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235402908,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 3235454412,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293297208,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295225296,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295283504,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296262500,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296309816,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296315836,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296377556,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277046802,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278170448,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278198842,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278798408,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278827490,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278831550,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278874622,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586733004,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587936329,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587973872,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588653583,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588688205,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692894,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588740906,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586600220,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587649433,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587686976,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365567,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400189,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588404878,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452858,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586930556,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588268105,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305648,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589089759,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124381,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129070,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177082,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
  "name": "sock_reset_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587038188,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588403273,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588440850,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129391,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589164205,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589168894,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589217148,
      "name": "sock_reset_flag",
      "external": false,
      "loc": "include/net/sock.h:836",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect_init"
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void sock_reset_flag(struct sock * sk, enum sock_flags flag)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
