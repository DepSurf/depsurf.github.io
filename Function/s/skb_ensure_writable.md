# Function: <code>skb_ensure_writable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586224480,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:4391",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224480,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586651328,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:4465",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651328,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586835952,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:4509",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835952,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586956640,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:4603",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956640,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587458096,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5034",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587458096,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587761488,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5114",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761488,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587896320,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5142",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896320,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588201952,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5335",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201952,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588407056,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407056,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269392,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5449",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589269392,
      "name": "skb_ensure_writable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269280,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5517",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589269280,
      "name": "skb_ensure_writable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589159392,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5605",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159392,
      "name": "skb_ensure_writable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589881888,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5680",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881888,
      "name": "skb_ensure_writable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skb_ensure_writable(struct sk_buff * skb, unsigned int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591411504,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5601",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_crc32c_csum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411504,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int skb_ensure_writable(struct sk_buff * skb, unsigned int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593176544,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5803",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_crc32c_csum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593176544,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int skb_ensure_writable(struct sk_buff * skb, unsigned int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593634144,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5860",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_crc32c_csum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593634144,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int skb_ensure_writable(struct sk_buff * skb, unsigned int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594409984,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5988",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/dev.c:skb_crc32c_csum_help",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594409984,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501923512,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501923512,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234683260,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234683260,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295341360,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295341360,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278234376,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278234376,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588013840,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013840,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587726928,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726928,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588345616,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict",
        "net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust",
        "net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588345616,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int skb_ensure_writable(struct sk_buff * skb, int write_len)
```

```json
{
  "name": "skb_ensure_writable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588481088,
      "name": "skb_ensure_writable",
      "external": true,
      "loc": "net/core/skbuff.c:5347",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:sk_skb_pull_data",
        "net/core/filter.c:bpf_skb_pull_data",
        "net/core/filter.c:bpf_skb_store_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481088,
      "name": "skb_ensure_writable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int write_len</code> ➡️ <code>unsigned int write_len</code>
</li>
</ul>
</details>
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
