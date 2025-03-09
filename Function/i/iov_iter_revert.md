# Function: <code>iov_iter_revert</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583453920,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:851",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_and_csum_datagram",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453920,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583634016,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:853",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_actor",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_and_csum_datagram",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634016,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583851040,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:983",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_actor",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_and_csum_datagram",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851040,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583934848,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_bio_actor",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934848,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113167,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132392,
      "name": "iov_iter_revert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584113136,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236320,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236320,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584646816,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1079",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646816,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584773600,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1086",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "drivers/tty/tty_io.c:do_tty_write",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773600,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584790224,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1183",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "drivers/tty/tty_io.c:do_tty_write",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790224,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585220416,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1039",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220416,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586059216,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1091",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059216,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587060952,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:915",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_mc_to_iter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/splice.c:iter_to_pipe",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043648,
      "name": "iov_iter_revert.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071587044080,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587301200,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:647",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/splice.c:iter_to_pipe",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587301200,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587586480,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:548",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "kernel/printk/printk.c:devkmsg_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/splice.c:iter_to_pipe",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:blkdev_write_iter",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/bio-integrity.c:bio_integrity_copy_user",
        "drivers/tty/tty_io.c:iterate_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587586480,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496112024,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496112024,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229437804,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229437804,
      "name": "iov_iter_revert",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290362064,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290362064,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275176882,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275176882,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584205056,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205056,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140272,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140272,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188816,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188816,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```

```json
{
  "name": "iov_iter_revert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584293248,
      "name": "iov_iter_revert",
      "external": true,
      "loc": "lib/iov_iter.c:1047",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293248,
      "name": "iov_iter_revert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void iov_iter_revert(struct iov_iter * i, size_t unroll)
```
</details>
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
