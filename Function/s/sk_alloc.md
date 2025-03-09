# Function: <code>sk_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190112,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1414",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190112,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586608512,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1404",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586608512,
      "name": "sk_alloc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792832,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1391",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/ipv6/af_inet6.c:inet6_create",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792832,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586924464,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1512",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924464,
      "name": "sk_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587416592,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1518",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587416592,
      "name": "sk_alloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587722528,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1530",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587722528,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587854704,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1526",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854704,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159104,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1652",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159104,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364368,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364368,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589226576,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1742",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226576,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224560,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1734",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224560,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589118256,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1766",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589118256,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836688,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1889",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836688,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591358272,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:2023",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358272,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593113472,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:2088",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593113472,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593565728,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:2146",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593565728,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594338320,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:2126",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594338320,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501866616,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501866616,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234634496,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234634496,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295277104,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295277104,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278194752,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278194752,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971152,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971152,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587684256,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684256,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588302928,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302928,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
struct sock * sk_alloc(struct net * net, int family, gfp_t priority, struct proto * prot, int kern)
```

```json
{
  "name": "sk_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588438304,
      "name": "sk_alloc",
      "external": true,
      "loc": "net/core/sock.c:1654",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_chr_open",
        "net/netlink/af_netlink.c:__netlink_create",
        "net/unix/af_unix.c:unix_create1",
        "net/packet/af_packet.c:packet_create",
        "net/xdp/xsk.c:xsk_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438304,
      "name": "sk_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
