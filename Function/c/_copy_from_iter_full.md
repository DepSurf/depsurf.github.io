# Function: <code>_copy_from_iter_full</code>

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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457760,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:596",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071583457760,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638256,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:596",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071583638256,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854464,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:712",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071583854464,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939360,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:756",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071583939360,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
        "net/ipv6/udp.c:udplite_getfrag",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132488,
      "name": "_copy_from_iter_full.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584117904,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241056,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071584241056,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584656336,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:778",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
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
      "addr": 18446744071584656336,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584767984,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:785",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
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
      "addr": 18446744071584767984,
      "name": "_copy_from_iter_full",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816864,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:822",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_generic_getfrag",
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
      "addr": 18446744071584816864,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1496
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496119088,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446603336496119088,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229443800,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 3229443800,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290383248,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 13835058055290383248,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275181518,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446743936275181518,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209792,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071584209792,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145008,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071584145008,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193552,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071584193552,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298016,
      "name": "_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:757",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/printk/printk.c:devkmsg_write",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udplite_getfrag",
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
      "addr": 18446744071584298016,
      "name": "_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool _copy_from_iter_full(void * addr, size_t bytes, struct iov_iter * i)
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
