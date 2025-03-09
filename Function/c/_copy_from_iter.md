# Function: <code>_copy_from_iter</code>

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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463232,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:576",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463232,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644096,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:576",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644096,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861968,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:692",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861968,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945776,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:736",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dio_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945776,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132551,
      "name": "_copy_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584122416,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584247728,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584247728,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660288,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:758",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660288,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770832,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:765",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770832,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805808,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:800",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805808,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1777
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585228624,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:714",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585228624,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1479
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:766",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/char/random.c:write_pool_user",
        "drivers/dax/super.c:dax_copy_from_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
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
      "addr": 18446744071594127640,
      "name": "_copy_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586073664,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1681
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:627",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/char/random.c:write_pool_user",
        "drivers/dax/super.c:dax_copy_from_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
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
      "addr": 18446744071596114255,
      "name": "_copy_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071587050704,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1488
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:383",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/char/random.c:write_pool_user",
        "drivers/dax/super.c:dax_copy_from_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
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
      "addr": 18446744071596639608,
      "name": "_copy_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587307056,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:253",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_write_iter",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "block/bio-integrity.c:bio_integrity_copy_user",
        "drivers/tty/tty_io.c:iterate_tty_write",
        "drivers/char/random.c:write_pool_user",
        "drivers/dax/super.c:dax_copy_from_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv4/ping.c:ping_common_sendmsg",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
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
      "addr": 18446744071597548162,
      "name": "_copy_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587593472,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1415
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496125728,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496125728,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229448864,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229448864,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290381952,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290381952,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1288
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275186480,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "lib/iov_iter.c:copy_page_from_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275186480,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584216464,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216464,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151680,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151680,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200224,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200224,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304736,
      "name": "_copy_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:737",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304736,
      "name": "_copy_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
size_t _copy_from_iter(void * addr, size_t bytes, struct iov_iter * i)
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
