# Function: <code>__put_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249680,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:453",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:single_open_net",
        "net/core/sock.c:sk_destruct",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249680,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586673920,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:453",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586673920,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586858368,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:484",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858368,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586981664,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:523",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981664,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479648,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:524",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:get_target_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479648,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587785728,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:591",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:get_target_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785728,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587918576,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:591",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_sk_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918576,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588227648,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:635",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227648,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588432288,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432288,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589301574,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:644",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_netns_get",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589298096,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589300252,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:645",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_netns_get",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296656,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589195852,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:636",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190544,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589917740,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912080,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591449238,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:637",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591443024,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593216806,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:656",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593210096,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593677254,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:657",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593670336,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594455334,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:661",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:bpf_iter_fini_seq_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/netkit.c:netkit_new_link",
        "net/core/sock.c:__sk_destruct",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_reload_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594448416,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501953600,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501953600,
      "name": "__put_net",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234709188,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234709188,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295376480,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295376480,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278257530,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278257530,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588039072,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039072,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587752160,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752160,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370848,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/netfilter/nfnetlink_log.c:nfulnl_instance_free_rcu",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370848,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __put_net(struct net * net)
```

```json
{
  "name": "__put_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588506512,
      "name": "__put_net",
      "external": true,
      "loc": "net/core/net_namespace.c:638",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_conn_free",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/proc_net.c:proc_tgid_net_readdir",
        "fs/proc/proc_net.c:proc_tgid_net_getattr",
        "fs/proc/proc_net.c:proc_tgid_net_lookup",
        "fs/proc/proc_net.c:single_release_net",
        "fs/proc/proc_net.c:single_open_net",
        "fs/proc/proc_net.c:seq_release_net",
        "fs/proc/proc_net.c:seq_open_net",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/sock.c:__sk_destruct",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc",
        "net/core/flow_dissector.c:skb_flow_dissector_prog_query",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_get_net_ns_capable",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506512,
      "name": "__put_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
