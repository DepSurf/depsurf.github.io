# Function: <code>siphash_3u32</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588241360,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588241360,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792784,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792784,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589171024,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171024,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589400944,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400944,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589856976,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856976,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590082768,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590082768,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585080608,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080608,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585229776,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229776,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112672,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112672,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585561344,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585561344,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713504,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:215",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713504,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595876064,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:215",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595876064,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596393440,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:215",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596393440,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597288672,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:215",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597288672,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503860968,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503860968,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236487668,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236487668,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297718464,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297718464,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279755164,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279755164,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685024,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685024,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589410816,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410816,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590128400,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590128400,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```

```json
{
  "name": "siphash_3u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590178784,
      "name": "siphash_3u32",
      "external": true,
      "loc": "lib/siphash.c:222",
      "file": "lib/siphash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/ipv4/route.c:__ip_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178784,
      "name": "siphash_3u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t * key)
```
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
