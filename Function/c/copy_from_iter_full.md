# Function: <code>copy_from_iter_full</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583443648,
      "name": "copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:574",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583443648,
      "name": "copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777902,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589516,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585745030,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275081,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333818,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587393117,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512541,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587530401,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640418,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587928241,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587939252,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588105780,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:121",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579811342,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742684,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586179337,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587795145,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587854362,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587909013,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035109,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054369,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165026,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588466257,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588475098,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588649148,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579847134,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942341,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440698,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588137597,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588199214,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588260036,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588387266,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400199,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588519484,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588825575,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588839459,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589004778,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:119",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579894238,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071583050885,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071586587835,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071588320352,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071588384990,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588448143,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577026,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588593415,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071588715660,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589048263,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071589063001,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589232168,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:157",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579200709,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929012,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234246,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586841081,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588718453,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787230,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588853504,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588990201,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005003,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589136723,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589501883,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589517807,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589677566,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579202927,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579979156,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340070,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586992553,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942308,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012078,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589076767,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214381,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589217917,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589360803,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589721677,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589741914,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071589901806,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224111,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025840,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674214,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813623,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833500,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968126,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590036943,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590187349,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590195565,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590341907,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590741229,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590760384,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071590932540,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579218095,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005264,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880345,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791446,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872311,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589869938,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590008670,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590067999,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590236337,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590247821,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590394787,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590800173,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590819841,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
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
      "addr": 18446744071590996902,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:150",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220575,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007024,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582910201,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815626,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587750839,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589775967,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922846,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982351,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590150431,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590161261,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590311907,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590726909,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590746952,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
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
      "addr": 18446744071590927270,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:158",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259019,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071580139877,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071583244587,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071584178634,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071588346792,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071590535356,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071590689246,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071590748622,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590930824,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071590939200,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071591098344,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071591539872,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071591563630,
      "name": "copy_from_iter_full",
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
      "addr": 18446744071591763782,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:166",
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579310825,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747066,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778862,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589750811,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592144101,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592317102,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592379680,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592571877,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592750316,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593228176,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593254606,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:175",
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375481,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362522,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475582,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591369963,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593968437,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594153934,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229360,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594433570,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594622156,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595128208,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595156585,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:192",
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384876,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592989,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707038,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591733581,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594345365,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594541261,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594616368,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594823377,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595014460,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595522592,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595552066,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:207",
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579415367,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824589,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954078,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205724,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592477383,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145051,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595343499,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595419184,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595635014,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595826940,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_common_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596366352,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596394761,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
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
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597076919,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:209",
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
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491163284,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495084140,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499987592,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502540412,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502615692,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502692952,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502838152,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502843620,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503002092,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503410380,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503436364,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446603336503632100,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225190584,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228478216,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3232515528,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3235248680,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235321996,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235394536,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3235537488,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235542020,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 3235694356,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236071720,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 3236095152,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 3236268920,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284062384,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288983168,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293310976,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296115216,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296213744,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296303612,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296489300,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296506672,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296693776,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297190688,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297217912,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 13835058055297450956,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271717666,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274348244,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277061732,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278705310,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278767670,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278823116,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278947432,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278959550,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279080048,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279407334,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279424124,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446743936279576476,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201775,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947892,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308806,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749577,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588548692,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618462,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588683151,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588820765,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824301,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588966979,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589326045,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589346282,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071589506174,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136735,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885812,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245942,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586616793,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588260676,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588330446,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588395135,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588532701,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588536237,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588678915,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589051037,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589071274,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071589232238,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579202847,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939428,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583292838,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586947113,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588880868,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589054638,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589119327,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589256941,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589260477,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589403363,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589762909,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783146,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071589947438,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579208127,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985716,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387430,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587046697,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022932,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589093822,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589159151,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589297701,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589301805,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589446739,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589813565,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udplite_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833884,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
      "addr": 18446744071589999784,
      "name": "copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:151",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>
