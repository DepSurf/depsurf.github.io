# Function: <code>tcp_md5_do_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586692768,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:915",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586692768,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587141344,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:923",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141344,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587338640,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:929",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587338640,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587470304,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:985",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470304,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587992304,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:989",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587992304,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588341312,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1051",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588341312,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588530736,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1061",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530736,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588941456,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1062",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941456,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589165888,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165888,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132640,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1103",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132640,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590180400,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1116",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590180400,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590094720,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1131",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094720,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590869600,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1146",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590869600,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592506672,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1154",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592506672,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 918
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594369136,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1233",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594369136,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594759408,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1240",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594759408,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int tcp_md5_do_add(struct sock * sk, const union tcp_ao_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595567184,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1396",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595567184,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502782560,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502782560,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235490428,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235490428,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296422592,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296422592,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278903886,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278903886,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772272,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772272,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588484208,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484208,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589208448,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589208448,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "tcp_md5_do_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589248720,
      "name": "tcp_md5_do_add",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:1069",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248720,
      "name": "tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 prefixlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, newkey, newkeylen, gfp</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, prefixlen, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, l3index, newkey, newkeylen, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, prefixlen, l3index, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, l3index, flags, newkey, newkeylen, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr * addr</code> ➡️ <code>const union tcp_ao_addr * addr</code>
</li>
</ul>
</details>
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
