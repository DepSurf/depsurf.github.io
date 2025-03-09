# Function: <code>__skb_ext_put</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877168,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:5720",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877168,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182448,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6080",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182448,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588388304,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388304,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248864,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6240",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:mptcp_v6_destroy",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248864,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246832,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6377",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246832,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141856,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6465",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141856,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861824,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6541",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861824,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591387552,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387552,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593151104,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6663",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_ext_maybe_cow",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593151104,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593604848,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6708",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_ext_maybe_cow",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593604848,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594379040,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6855",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:__skb_ext_set",
        "net/core/skbuff.c:skb_ext_maybe_cow",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594379040,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501896584,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501896584,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234662412,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234662412,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295312016,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295312016,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278218548,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278217988,
      "name": "__skb_ext_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446743936278218058,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587995088,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995088,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587708192,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708192,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588326864,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326864,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __skb_ext_put(struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588462288,
      "name": "__skb_ext_put",
      "external": true,
      "loc": "net/core/skbuff.c:6097",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_ext_del",
        "net/core/skbuff.c:skb_ext_add",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462288,
      "name": "__skb_ext_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __skb_ext_put(struct skb_ext * ext)
```
</details>
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
