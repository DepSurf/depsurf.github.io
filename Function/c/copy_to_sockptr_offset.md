# Function: <code>copy_to_sockptr_offset</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_sockptr_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590902257,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
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
  "name": "copy_to_sockptr_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590831521,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
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
  "name": "copy_to_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581184420,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_btf_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591650771,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
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
  "name": "copy_to_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581469999,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593345150,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void * src, size_t size)
```

```json
{
  "name": "copy_to_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796784,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line"
      ]
    },
    {
      "addr": 18446744071585614890,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777307,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029606,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593134412,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593534426,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_get_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594187948,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594263238,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    },
    {
      "addr": 18446744071594557579,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594713450,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595103937,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter"
      ],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt"
      ]
    },
    {
      "addr": 18446744071595171760,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_msfget"
      ]
    },
    {
      "addr": 18446744071595246960,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
      ]
    },
    {
      "addr": 18446744071595294975,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796784,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071594228304,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071595092448,
      "name": "copy_to_sockptr_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071595171760,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071595246960,
      "name": "copy_to_sockptr_offset.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void * src, size_t size)
```

```json
{
  "name": "copy_to_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581970480,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line"
      ]
    },
    {
      "addr": 18446744071582228912,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_parse"
      ]
    },
    {
      "addr": 18446744071585846700,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586010395,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266423,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593585074,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594002314,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_get_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594574407,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594648644,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    },
    {
      "addr": 18446744071594949307,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595105562,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595498897,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter"
      ],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt"
      ]
    },
    {
      "addr": 18446744071595567328,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_msfget"
      ]
    },
    {
      "addr": 18446744071595642400,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
      ]
    },
    {
      "addr": 18446744071595689999,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:58",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970480,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582228912,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071594615312,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071595486192,
      "name": "copy_to_sockptr_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071595567328,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071595642400,
      "name": "copy_to_sockptr_offset.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void * src, size_t size)
```

```json
{
  "name": "copy_to_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582101056,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line"
      ]
    },
    {
      "addr": 18446744071582384864,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_parse"
      ]
    },
    {
      "addr": 18446744071582531497,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586096700,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586258251,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586520010,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594360544,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594786634,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_get_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595378449,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595452940,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    },
    {
      "addr": 18446744071595761659,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget",
        "net/ipv4/igmp.c:ip_mc_msfget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595918234,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595989421,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ao.c:tcp_ao_get_repair",
        "net/ipv4/tcp_ao.c:tcp_ao_get_sock_info",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596342444,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter"
      ],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt"
      ]
    },
    {
      "addr": 18446744071596410192,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_msfget"
      ]
    },
    {
      "addr": 18446744071596489712,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
      ]
    },
    {
      "addr": 18446744071596537759,
      "name": "copy_to_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:81",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101056,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582384864,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071595418400,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071596328816,
      "name": "copy_to_sockptr_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071596410192,
      "name": "copy_to_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071596489712,
      "name": "copy_to_sockptr_offset.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void * src, size_t size)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
