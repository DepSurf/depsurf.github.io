# Function: <code>sock_prot_inuse_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187056,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:2711",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_release",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187056,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586607392,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:2779",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607392,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586791840,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:2801",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586791840,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586915680,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:2983",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915680,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407632,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3043",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407632,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587711088,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3118",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711088,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587844400,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3069",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844400,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148720,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148720,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353984,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353984,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589213680,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3361",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589213680,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212480,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3313",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212480,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589106016,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3336",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106016,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589823744,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3462",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589823744,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592141604,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592355328,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592358868,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592565282,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592588410,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592749871,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592996759,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593207268,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593457376,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593473253,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593622252,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1479",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
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
  "name": "sock_prot_inuse_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593965475,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594194561,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594204475,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594425810,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594443317,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594621439,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594885875,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595102461,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595374512,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595393701,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595551388,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1537",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
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
  "name": "sock_prot_inuse_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594342371,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594581720,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594591389,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594818393,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594833636,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595013564,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595278547,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595496811,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595771376,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595787210,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596059596,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596092421,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596147584,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1528",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_destroy",
        "net/mptcp/token.c:mptcp_token_accept",
        "net/mptcp/token.c:mptcp_token_new_connect"
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
  "name": "sock_prot_inuse_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141957,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595393248,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595395011,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595629689,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595644436,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_unhash",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595825564,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596119283,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596340237,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596620032,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596637226,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596925660,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980544,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597021296,
      "name": "sock_prot_inuse_add",
      "external": false,
      "loc": "include/net/sock.h:1503",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_destroy",
        "net/mptcp/token.c:mptcp_token_accept",
        "net/mptcp/token.c:mptcp_token_new_connect"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501866464,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501866464,
      "name": "sock_prot_inuse_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234626108,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234626108,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295263312,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295263312,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278185694,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278185694,
      "name": "sock_prot_inuse_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960768,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960768,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587673872,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587673872,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292544,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292544,
      "name": "sock_prot_inuse_add",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```

```json
{
  "name": "sock_prot_inuse_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427616,
      "name": "sock_prot_inuse_add",
      "external": true,
      "loc": "net/core/sock.c:3232",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427616,
      "name": "sock_prot_inuse_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void sock_prot_inuse_add(struct net * net, struct proto * prot, int val)
```
</details>
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
