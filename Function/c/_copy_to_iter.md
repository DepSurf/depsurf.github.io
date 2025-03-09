# Function: <code>_copy_to_iter</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583461568,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:558",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461568,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642048,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:558",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642048,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860208,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:558",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860208,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 975
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943760,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:602",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943760,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125744,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125744,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584245584,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245584,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584658752,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:621",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_read",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658752,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1006
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584769840,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:630",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/tty/tty_io.c:iterate_tty_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769840,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584812032,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:651",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812032,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1953
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236880,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:616",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236880,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:661",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/dax/super.c:dax_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127716,
      "name": "_copy_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586075888,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:521",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/dax/super.c:dax_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114342,
      "name": "_copy_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071587052416,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:310",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/dax/super.c:dax_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596639456,
      "name": "_copy_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587305040,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:179",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "fs/pipe.c:pipe_read",
        "fs/seq_file.c:seq_read_iter",
        "fs/seq_file.c:seq_read_iter",
        "fs/eventfd.c:eventfd_read",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/configfs/file.c:configfs_read_iter",
        "block/bio-integrity.c:bio_integrity_free",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/dax/super.c:dax_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/core/datagram.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548141,
      "name": "_copy_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587592032,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1410
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496123520,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496123520,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229446812,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229446812,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1128
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290375088,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290375088,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1560
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275183994,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275183994,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214320,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214320,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149536,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149536,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198080,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198080,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302576,
      "name": "_copy_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:603",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "net/core/datagram.c:simple_copy_to_iter",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302576,
      "name": "_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
size_t _copy_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
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
