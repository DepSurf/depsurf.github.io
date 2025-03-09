# Function: <code>copy_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t copy_to_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022720,
      "name": "copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:386",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_do_io",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022720,
      "name": "copy_to_iter",
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
size_t copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320352,
      "name": "copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:359",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_do_io",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320352,
      "name": "copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
size_t copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445184,
      "name": "copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:538",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445184,
      "name": "copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581636366,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462871,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585749284,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586969274,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382058,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587525590,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587921771,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588107408,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:103",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581781197,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643422,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586186350,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587467338,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912162,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588048438,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588456987,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588650816,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583861617,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446514,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261726,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587772323,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247455,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402416,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588819218,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588999670,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:101",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138976,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945631,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586594002,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587441998,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587907765,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437518,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592298,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589041164,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223354,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309648,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584127696,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586847342,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723574,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216901,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588845922,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589003689,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495043,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589680658,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408645,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247542,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586981694,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587928118,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588419461,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072344,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228078,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589718880,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589906146,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582117871,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457360,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701976,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584660102,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818386,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588778101,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287285,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590033760,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200954,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590740164,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590935142,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164255,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309034,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514184,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773208,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880476,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916328,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770646,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586515922,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:iterate_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876098,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588798773,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285941,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590078040,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590251479,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590799208,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590999366,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:132",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582188746,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582338628,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541960,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582802200,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582910336,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944021,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815126,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586400974,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587754882,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588683733,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589179845,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589992464,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169752,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590725895,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590929742,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:140",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582506115,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659156,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858008,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126753,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244730,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279173,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583293638,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585239750,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586927662,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588351830,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367941,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589898309,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762407,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590950602,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591542320,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591766286,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:148",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579469892,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028234,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583199257,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420639,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615911,
      "name": "copy_to_iter",
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
      "addr": 18446744071583747201,
      "name": "copy_to_iter",
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
      "addr": 18446744071583762962,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783468,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799336,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586078646,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588221780,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500696,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740598,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591427637,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592395168,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592591495,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593231864,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593482522,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579561844,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592442,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775449,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008351,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219338,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362657,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584379666,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584402317,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419800,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587054038,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589635380,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936572,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591359094,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593194005,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594246335,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594454892,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595132465,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595399067,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579574132,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808993,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992665,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584231122,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584448826,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584593124,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584601800,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608050,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584630877,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648379,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306438,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589939023,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590244252,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591719766,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593653253,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594632463,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594846221,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595528024,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595801957,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:191",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579603876,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584015217,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205289,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445906,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584671594,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_inline_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824724,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584833769,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840050,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584862701,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584880782,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205211,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590277894,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590585276,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592463446,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594429109,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter",
        "net/core/datagram.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595436040,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595657225,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596370560,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596652566,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:193",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494009956,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496125548,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499974736,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501156792,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501938828,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502677948,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502858560,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503418956,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503623316,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227475044,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 3229448644,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3232520576,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234693668,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3235381928,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235555812,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236078856,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236273668,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287661936,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290377912,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293319320,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294676576,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295359680,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296287840,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296500340,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297186756,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297445848,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273523132,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275185570,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277054644,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277871584,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278246180,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278817210,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278958484,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279400928,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279575350,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582377381,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216278,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586738702,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587559094,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588026245,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588678728,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588834462,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589323248,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589510514,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582315077,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151494,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605918,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327174,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587739333,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390712,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588546398,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048240,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236578,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582367861,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200038,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586936254,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884262,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588358021,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114904,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589270638,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760112,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951778,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
  "name": "copy_to_iter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582447557,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584304550,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044385,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001254,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493573,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:simple_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154728,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589310793,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589810779,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590003266,
      "name": "copy_to_iter",
      "external": false,
      "loc": "include/linux/uio.h:133",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_recvmsg"
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * addr</code> ➡️ <code>const void * addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
size_t copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>
