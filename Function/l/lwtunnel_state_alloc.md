# Function: <code>lwtunnel_state_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586440144,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:30",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586440144,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884928,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:55",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884928,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076832,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:60",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076832,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587204384,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:60",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587204384,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718656,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:62",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718656,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588052256,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:62",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588052256,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220544,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:62",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220544,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554784,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554784,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588771664,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771664,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589643600,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:59",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643600,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667280,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:59",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667280,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589558976,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:59",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589558976,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590304016,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:64",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304016,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591888512,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:64",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591888512,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593690704,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:67",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593690704,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594171504,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:67",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594171504,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594968048,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:67",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594968048,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502338192,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502338192,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235077604,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235077604,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295859264,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295859264,
      "name": "lwtunnel_state_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278559786,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278559786,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588378048,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378048,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588090736,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090736,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710224,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710224,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct lwtunnel_state * lwtunnel_state_alloc(int encap_len)
```

```json
{
  "name": "lwtunnel_state_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588850432,
      "name": "lwtunnel_state_alloc",
      "external": true,
      "loc": "net/core/lwtunnel.c:57",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588850432,
      "name": "lwtunnel_state_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
