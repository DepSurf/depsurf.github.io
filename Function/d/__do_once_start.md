# Function: <code>__do_once_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583042944,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:36",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042944,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335712,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:36",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335712,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583461136,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:36",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461136,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482832,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:36",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482832,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663824,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663824,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881392,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881392,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965056,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965056,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144944,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144944,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267392,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267392,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584675424,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584675424,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584792976,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792976,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584837168,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837168,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585256523,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324417,
      "name": "__do_once_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585256464,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586098979,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594128893,
      "name": "__do_once_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586098912,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587083475,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115909,
      "name": "__do_once_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587083408,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587342147,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641648,
      "name": "__do_once_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587342080,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587625619,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:42",
      "file": "lib/once.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549713,
      "name": "__do_once_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587625552,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496150008,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496150008,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229471348,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229471348,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290410432,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290410432,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275204232,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275204232,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236128,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236128,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584171328,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171328,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219888,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/netfilter/nf_conntrack_core.c:nf_ct_get_id",
        "net/netfilter/nf_conntrack_core.c:hash_conntrack_raw",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash",
        "net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219888,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool __do_once_start(bool * done, long unsigned int * flags)
```

```json
{
  "name": "__do_once_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584324720,
      "name": "__do_once_start",
      "external": true,
      "loc": "lib/once.c:37",
      "file": "lib/once.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324720,
      "name": "__do_once_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
