# Function: <code>fib_table_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586835392,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1269",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835392,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587284544,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1267",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284544,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587485888,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1377",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485888,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587623120,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1298",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587623120,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588147504,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1296",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147504,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588508704,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1316",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588508704,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703760,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1316",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703760,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589121760,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589121760,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589345840,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589345840,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328608,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1395",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328608,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1798
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590381648,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1395",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590381648,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1498
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590297312,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1432",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590297312,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1511
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1436",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592728471,
      "name": "fib_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071591084288,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1799
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1442",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594614859,
      "name": "fib_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
    },
    {
      "addr": 18446744071592734560,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1871
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1444",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596349717,
      "name": "fib_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
    },
    {
      "addr": 18446744071594605392,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1876
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1444",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596878709,
      "name": "fib_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 18446744071594997296,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1445",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597802803,
      "name": "fib_table_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 18446744071595809808,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1934
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502985968,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502985968,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1680
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235675488,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235675488,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1844
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296672128,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296672128,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2080
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279062972,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279062972,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1452
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588952016,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588952016,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663952,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663952,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589388400,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388400,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int fib_table_lookup(struct fib_table * tb, const struct flowi4 * flp, struct fib_result * res, int fib_flags)
```

```json
{
  "name": "fib_table_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431424,
      "name": "fib_table_lookup",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1312",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431424,
      "name": "fib_table_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1482
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
