# Function: <code>skb_gso_validate_network_len</code>

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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587734688,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5035",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734688,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868848,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5063",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868848,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173712,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5248",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173712,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588378848,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378848,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243296,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5362",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_finish_output_gso",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243296,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242592,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5429",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_finish_output_gso",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242592,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589137568,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5517",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137568,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589856480,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5592",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856480,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591381888,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5513",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381888,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593142880,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5715",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593142880,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594039360,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/gso.c:253",
      "file": "net/core/gso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594039360,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594829744,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/gso.c:253",
      "file": "net/core/gso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594829744,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501890184,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501890184,
      "name": "skb_gso_validate_network_len",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234652164,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234652164,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295299248,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295299248,
      "name": "skb_gso_validate_network_len",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278208046,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278208046,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587985632,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587985632,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587698736,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587698736,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588317408,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317408,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
```

```json
{
  "name": "skb_gso_validate_network_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588452752,
      "name": "skb_gso_validate_network_len",
      "external": true,
      "loc": "net/core/skbuff.c:5260",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output",
        "net/xfrm/xfrm_device.c:xfrm_dev_offload_ok",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452752,
      "name": "skb_gso_validate_network_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool skb_gso_validate_network_len(const struct sk_buff * skb, unsigned int mtu)
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
