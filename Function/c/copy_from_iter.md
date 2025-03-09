# Function: <code>copy_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021344,
      "name": "copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:407",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021344,
      "name": "copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
size_t copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583321472,
      "name": "copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:374",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321472,
      "name": "copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
size_t copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446784,
      "name": "copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:555",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446784,
      "name": "copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 891
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586498182,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:112",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586972432,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:112",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453375,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:112",
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586965586,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587470640,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974965,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580744871,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261950,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587775605,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324768,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:110",
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138773,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442222,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587905999,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180264,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513819,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309484,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723350,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588214815,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588506304,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588917921,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408455,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587927878,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588419602,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712313,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589141729,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582701877,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588777861,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589284946,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579115,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112206,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582773109,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917973,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516788,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799029,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283202,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589589051,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159662,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582802101,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944725,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586402132,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588683493,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177138,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589647435,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073260,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:149",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259019,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139877,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126657,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244587,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279877,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583293167,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178634,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928980,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588346792,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367701,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899362,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590401759,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590535356,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590689246,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748622,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590847396,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590930824,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590939200,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591098344,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591539872,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591563630,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591763782,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579310825,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282591,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615849,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747066,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785741,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799870,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778862,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223707,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496050,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589750811,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591428790,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591996552,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592144101,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592317102,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592379680,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592483530,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592571877,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592582048,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592750316,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593228176,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593254606,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593476830,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593751159,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375481,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491519,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219276,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362522,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584403741,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420350,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475582,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589632850,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936866,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591369963,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593195222,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593811304,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593968437,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594153934,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229360,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594339386,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594433570,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594444224,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594622156,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595128208,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595156585,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595396461,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595688119,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:184",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384876,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580563356,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748875,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584448764,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592989,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632061,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648942,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707038,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937634,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590242834,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591733581,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593654550,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594185592,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594345365,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594541261,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594616368,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594823377,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594829696,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595014460,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595522592,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595552066,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595792086,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596199146,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:199",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579415367,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624188,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865819,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584671532,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824589,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584864077,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584881342,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954078,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205724,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590276174,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:iterate_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590583858,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592477383,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430406,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594982264,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145051,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595343499,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595419184,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595635014,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595641376,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595826940,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596366352,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596394761,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596642707,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596985463,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597076919,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:201",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494009768,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501156504,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501935796,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502277716,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502757540,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227474816,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 3234693864,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3235016244,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3235462036,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287662240,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294676176,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295356708,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295774624,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296386692,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273522998,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277871386,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278244514,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278511928,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278880988,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582377191,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587558854,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588026386,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319049,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588748113,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582314887,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326934,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587739474,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588031833,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588460065,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582367671,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884022,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588358162,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588650873,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589184289,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
  "name": "copy_from_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582447367,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001014,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493714,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588790681,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224353,
      "name": "copy_from_iter",
      "external": false,
      "loc": "include/linux/uio.h:142",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
size_t copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>
