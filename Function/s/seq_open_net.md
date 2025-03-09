# Function: <code>seq_open_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_open_net(struct inode * ino, struct file * f, const struct seq_operations * ops, int size)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581492448,
      "name": "seq_open_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:39",
      "file": "fs/proc/proc_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_seq_open",
        "net/core/net-procfs.c:dev_mc_seq_open",
        "net/core/net-procfs.c:ptype_seq_open",
        "net/core/net-procfs.c:dev_seq_open",
        "net/netlink/af_netlink.c:netlink_seq_open",
        "net/netfilter/nf_log.c:nflog_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/raw.c:raw_v4_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/arp.c:arp_seq_open",
        "net/ipv4/igmp.c:igmp_mcf_seq_open",
        "net/ipv4/igmp.c:igmp_mc_seq_open",
        "net/ipv4/fib_trie.c:fib_route_seq_open",
        "net/ipv4/fib_trie.c:fib_trie_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv4/ipmr.c:ipmr_mfc_open",
        "net/ipv4/ipmr.c:ipmr_vif_open",
        "net/unix/af_unix.c:unix_seq_open",
        "net/ipv6/anycast.c:ac6_seq_open",
        "net/ipv6/addrconf.c:if6_seq_open",
        "net/ipv6/ip6_fib.c:ipv6_route_open",
        "net/ipv6/mcast.c:igmp6_mcf_seq_open",
        "net/ipv6/mcast.c:igmp6_mc_seq_open",
        "net/ipv6/ip6mr.c:ipmr_mfc_open",
        "net/ipv6/ip6mr.c:ip6mr_vif_open",
        "net/packet/af_packet.c:packet_seq_open",
        "net/wireless/wext-proc.c:seq_open_wireless"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492448,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_open_net(struct inode * ino, struct file * f, const struct seq_operations * ops, int size)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581677184,
      "name": "seq_open_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:39",
      "file": "fs/proc/proc_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_seq_open",
        "net/core/net-procfs.c:dev_mc_seq_open",
        "net/core/net-procfs.c:ptype_seq_open",
        "net/core/net-procfs.c:dev_seq_open",
        "net/netlink/af_netlink.c:netlink_seq_open",
        "net/netfilter/nf_log.c:nflog_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/raw.c:raw_v4_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/arp.c:arp_seq_open",
        "net/ipv4/igmp.c:igmp_mcf_seq_open",
        "net/ipv4/igmp.c:igmp_mc_seq_open",
        "net/ipv4/fib_trie.c:fib_route_seq_open",
        "net/ipv4/fib_trie.c:fib_trie_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv4/ipmr.c:ipmr_mfc_open",
        "net/ipv4/ipmr.c:ipmr_vif_open",
        "net/unix/af_unix.c:unix_seq_open",
        "net/ipv6/anycast.c:ac6_seq_open",
        "net/ipv6/addrconf.c:if6_seq_open",
        "net/ipv6/ip6_fib.c:ipv6_route_open",
        "net/ipv6/mcast.c:igmp6_mcf_seq_open",
        "net/ipv6/mcast.c:igmp6_mc_seq_open",
        "net/ipv6/ip6mr.c:ipmr_mfc_open",
        "net/ipv6/ip6mr.c:ip6mr_vif_open",
        "net/packet/af_packet.c:packet_seq_open",
        "net/wireless/wext-proc.c:seq_open_wireless"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677184,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_open_net(struct inode * ino, struct file * f, const struct seq_operations * ops, int size)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581765328,
      "name": "seq_open_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:40",
      "file": "fs/proc/proc_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_seq_open",
        "net/core/net-procfs.c:dev_mc_seq_open",
        "net/core/net-procfs.c:ptype_seq_open",
        "net/core/net-procfs.c:dev_seq_open",
        "net/netlink/af_netlink.c:netlink_seq_open",
        "net/netfilter/nf_log.c:nflog_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/raw.c:raw_v4_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/arp.c:arp_seq_open",
        "net/ipv4/igmp.c:igmp_mcf_seq_open",
        "net/ipv4/igmp.c:igmp_mc_seq_open",
        "net/ipv4/fib_trie.c:fib_route_seq_open",
        "net/ipv4/fib_trie.c:fib_trie_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv4/ipmr.c:ipmr_mfc_open",
        "net/ipv4/ipmr.c:ipmr_vif_open",
        "net/unix/af_unix.c:unix_seq_open",
        "net/ipv6/anycast.c:ac6_seq_open",
        "net/ipv6/addrconf.c:if6_seq_open",
        "net/ipv6/ip6_fib.c:ipv6_route_open",
        "net/ipv6/mcast.c:igmp6_mcf_seq_open",
        "net/ipv6/mcast.c:igmp6_mc_seq_open",
        "net/ipv6/ip6mr.c:ipmr_mfc_open",
        "net/ipv6/ip6mr.c:ip6mr_vif_open",
        "net/packet/af_packet.c:packet_seq_open",
        "net/wireless/wext-proc.c:seq_open_wireless"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765328,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_open_net(struct inode * ino, struct file * f, const struct seq_operations * ops, int size)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581819344,
      "name": "seq_open_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:41",
      "file": "fs/proc/proc_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_seq_open",
        "net/core/net-procfs.c:dev_mc_seq_open",
        "net/core/net-procfs.c:ptype_seq_open",
        "net/core/net-procfs.c:dev_seq_open",
        "net/netlink/af_netlink.c:netlink_seq_open",
        "net/netfilter/nf_log.c:nflog_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/raw.c:raw_v4_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/arp.c:arp_seq_open",
        "net/ipv4/igmp.c:igmp_mcf_seq_open",
        "net/ipv4/igmp.c:igmp_mc_seq_open",
        "net/ipv4/fib_trie.c:fib_route_seq_open",
        "net/ipv4/fib_trie.c:fib_trie_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv4/ipmr.c:ipmr_mfc_open",
        "net/ipv4/ipmr.c:ipmr_vif_open",
        "net/unix/af_unix.c:unix_seq_open",
        "net/ipv6/anycast.c:ac6_seq_open",
        "net/ipv6/addrconf.c:if6_seq_open",
        "net/ipv6/ip6_fib.c:ipv6_route_open",
        "net/ipv6/mcast.c:igmp6_mcf_seq_open",
        "net/ipv6/mcast.c:igmp6_mc_seq_open",
        "net/ipv6/ip6mr.c:ipmr_mfc_open",
        "net/ipv6/ip6mr.c:ip6mr_vif_open",
        "net/packet/af_packet.c:packet_seq_open",
        "net/wireless/wext-proc.c:seq_open_wireless"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819344,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int seq_open_net(struct inode * ino, struct file * f, const struct seq_operations * ops, int size)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968912,
      "name": "seq_open_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:41",
      "file": "fs/proc/proc_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_seq_open",
        "net/core/net-procfs.c:dev_mc_seq_open",
        "net/core/net-procfs.c:ptype_seq_open",
        "net/core/net-procfs.c:dev_seq_open",
        "net/netlink/af_netlink.c:netlink_seq_open",
        "net/netfilter/nf_log.c:nflog_open",
        "net/ipv4/tcp_ipv4.c:tcp_seq_open",
        "net/ipv4/raw.c:raw_v4_seq_open",
        "net/ipv4/udp.c:udp_seq_open",
        "net/ipv4/arp.c:arp_seq_open",
        "net/ipv4/igmp.c:igmp_mcf_seq_open",
        "net/ipv4/igmp.c:igmp_mc_seq_open",
        "net/ipv4/fib_trie.c:fib_route_seq_open",
        "net/ipv4/fib_trie.c:fib_trie_seq_open",
        "net/ipv4/ping.c:ping_seq_open",
        "net/ipv4/ipmr.c:ipmr_mfc_open",
        "net/ipv4/ipmr.c:ipmr_vif_open",
        "net/unix/af_unix.c:unix_seq_open",
        "net/ipv6/anycast.c:ac6_seq_open",
        "net/ipv6/addrconf.c:if6_seq_open",
        "net/ipv6/ip6_fib.c:ipv6_route_open",
        "net/ipv6/mcast.c:igmp6_mcf_seq_open",
        "net/ipv6/mcast.c:igmp6_mc_seq_open",
        "net/ipv6/ip6mr.c:ipmr_mfc_open",
        "net/ipv6/ip6mr.c:ip6mr_vif_open",
        "net/packet/af_packet.c:packet_seq_open",
        "net/wireless/wext-proc.c:seq_open_wireless"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968912,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154320,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:41",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154320,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249024,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:57",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249024,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413728,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413728,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512672,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512672,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816944,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816944,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889680,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:42",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889680,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918144,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:42",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918144,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252752,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:42",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252752,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752592,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:42",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752592,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368496,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:39",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368496,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596848,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:39",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596848,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584828544,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:39",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828544,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494140904,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494140904,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227587812,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227587812,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287817248,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287817248,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273619854,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273619854,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481408,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481408,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582418640,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418640,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471888,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471888,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int seq_open_net(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_open_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552432,
      "name": "seq_open_net",
      "external": false,
      "loc": "fs/proc/proc_net.c:58",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552432,
      "name": "seq_open_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * ino</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * f</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct seq_operations * ops</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
</ul>
</details>
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
