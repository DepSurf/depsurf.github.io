# Function: <code>tcp_rate_gen</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, struct skb_mstamp * now, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368896,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:108",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368896,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587502336,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:108",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587502336,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024608,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:108",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024608,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588375664,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:108",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375664,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566080,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:109",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566080,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977216,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977216,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201664,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201664,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590173904,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590173904,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590223152,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590223152,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590137216,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137216,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592722068,
      "name": "tcp_rate_gen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071590917424,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:117",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594608305,
      "name": "tcp_rate_gen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071592557488,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:117",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596343698,
      "name": "tcp_rate_gen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071594417088,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:117",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596872734,
      "name": "tcp_rate_gen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071594806432,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:117",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597796706,
      "name": "tcp_rate_gen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071595617664,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502822008,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502822008,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235523704,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235523704,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296469920,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296469920,
      "name": "tcp_rate_gen",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278935812,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278935812,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588808048,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808048,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588519984,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519984,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589244224,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589244224,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample * rs)
```

```json
{
  "name": "tcp_rate_gen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284800,
      "name": "tcp_rate_gen",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:110",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284800,
      "name": "tcp_rate_gen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void tcp_rate_gen(struct sock * sk, u32 delivered, u32 lost, struct skb_mstamp * now, struct rate_sample * rs)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct skb_mstamp * now</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, delivered, lost, now, rs</code> ➡️ <code>sk, delivered, lost, rs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_sack_reneg</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, delivered, lost, rs</code> ➡️ <code>sk, delivered, lost, is_sack_reneg, rs</code>
</li>
</ul>
</details>
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
