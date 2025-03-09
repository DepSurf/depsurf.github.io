# Function: <code>proc_create_net_data</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153952,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:84",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153952,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248640,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:100",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248640,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413344,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413344,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512288,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512288,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816016,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:120",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816016,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888832,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:104",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888832,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917296,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:104",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917296,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251904,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:104",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251904,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751648,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:117",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751648,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367440,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:114",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367440,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595792,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:114",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595792,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827488,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:114",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827488,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494140336,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494140336,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227587396,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227587396,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287816672,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287816672,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273619264,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273619264,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481024,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481024,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582418256,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418256,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471504,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/netfilter/nfnetlink_queue.c:nfnl_queue_net_init",
        "net/netfilter/nfnetlink_log.c:nfnl_log_net_init",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471504,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```

```json
{
  "name": "proc_create_net_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552048,
      "name": "proc_create_net_data",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:proto_init_net",
        "net/core/net-procfs.c:dev_mc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/core/net-procfs.c:dev_proc_net_init",
        "net/netlink/af_netlink.c:netlink_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init_net",
        "net/ipv4/raw.c:raw_init_net",
        "net/ipv4/udp.c:udp4_proc_init_net",
        "net/ipv4/udplite.c:udplite4_proc_init_net",
        "net/ipv4/arp.c:arp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/igmp.c:igmp_net_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/ping.c:ping_v4_proc_init_net",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/ipv4/ipmr.c:ipmr_net_init",
        "net/unix/af_unix.c:unix_net_init",
        "net/ipv6/anycast.c:ac6_proc_init",
        "net/ipv6/addrconf.c:if6_proc_net_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/udp.c:udp6_proc_init",
        "net/ipv6/udplite.c:udplite6_proc_init_net",
        "net/ipv6/raw.c:raw6_init_net",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcp6_proc_init",
        "net/ipv6/ping.c:ping_v6_proc_init_net",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/ipv6/ip6mr.c:ip6mr_net_init",
        "net/packet/af_packet.c:packet_net_init",
        "net/wireless/wext-proc.c:wext_proc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552048,
      "name": "proc_create_net_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct proc_dir_entry * proc_create_net_data(const char * name, umode_t mode, struct proc_dir_entry * parent, const struct seq_operations * ops, unsigned int state_size, void * data)
```
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
