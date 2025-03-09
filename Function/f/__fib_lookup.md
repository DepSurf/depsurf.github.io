# Function: <code>__fib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867184,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:50",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867184,
      "name": "__fib_lookup",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316960,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:50",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316960,
      "name": "__fib_lookup",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587519536,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:50",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587519536,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587657616,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:71",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657616,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182256,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182256,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588537424,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588537424,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588733680,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733680,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589165728,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165728,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389712,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389712,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590376576,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:79",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376576,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590434032,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:80",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434032,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590359744,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:80",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590359744,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591151360,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:80",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591151360,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592807600,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592807600,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594683040,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594683040,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595075360,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595075360,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595888160,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:81",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595888160,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503034456,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503034456,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235723080,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235723080,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296734288,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296734288,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279103076,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279103076,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588995888,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588995888,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588718944,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718944,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432272,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432272,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __fib_lookup(struct net * net, struct flowi4 * flp, struct fib_result * res, unsigned int flags)
```

```json
{
  "name": "__fib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589475920,
      "name": "__fib_lookup",
      "external": true,
      "loc": "net/ipv4/fib_rules.c:78",
      "file": "net/ipv4/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589475920,
      "name": "__fib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
