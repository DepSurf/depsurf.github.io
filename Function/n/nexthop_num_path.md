# Function: <code>nexthop_num_path</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588455953,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588767902,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087358,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589113524,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122738,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158129,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413778,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588661665,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588991675,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589311518,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589337917,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589346816,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589382241,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589638018,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589519721,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589949546,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590289824,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590316456,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_find_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590329759,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590367942,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:178",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589527785,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589990759,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590342656,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590369688,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_find_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590425254,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:212",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589425701,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589904802,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590258554,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590285768,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_find_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590350522,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590155456,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590670662,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591042973,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591072292,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_find_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591085400,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591139625,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591715865,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592296982,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592691319,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592721613,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_find_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592735704,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592794390,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
unsigned int nexthop_num_path(const struct nexthop * nh)
```

```json
{
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593502966,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594132598,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594560359,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594591933,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_find_info"
      ]
    },
    {
      "addr": 18446744071594606531,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594668598,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594572240,
      "name": "nexthop_num_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071596345792,
      "name": "nexthop_num_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
unsigned int nexthop_num_path(const struct nexthop * nh)
```

```json
{
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593977273,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594519622,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594952103,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594983549,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_find_info"
      ]
    },
    {
      "addr": 18446744071594998445,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595061014,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594964048,
      "name": "nexthop_num_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071596874823,
      "name": "nexthop_num_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
unsigned int nexthop_num_path(const struct nexthop * nh)
```

```json
{
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594761918,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595322326,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595764519,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595796045,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_nlmsg_size",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_find_info"
      ]
    },
    {
      "addr": 18446744071595810959,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595874022,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:288",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595776544,
      "name": "nexthop_num_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071597798917,
      "name": "nexthop_num_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502208344,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502596332,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502948560,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502976488,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502987104,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503025180,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503320464,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234959076,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235302072,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 3235637880,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3235666400,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235676636,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235714804,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 3235989652,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295689872,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296187052,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296624076,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296660064,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296673180,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296722792,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297081228,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278464436,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278749150,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279033202,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279055230,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279063882,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279095604,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279337864,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588268401,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598059,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588917694,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588944093,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952992,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588988417,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242386,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587981217,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310043,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588629630,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588656029,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588664928,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588700353,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588967378,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588600225,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589034235,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354078,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380477,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589389376,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589424801,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589679250,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
  "name": "nexthop_num_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588737916,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_ipv4_fib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589073260,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:fib_dump_info_fnhe",
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589396526,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423469,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:fib_release_info",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589432430,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468369,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728386,
      "name": "nexthop_num_path",
      "external": false,
      "loc": "include/net/nexthop.h:135",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int nexthop_num_path(const struct nexthop * nh)
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
