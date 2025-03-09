# Function: <code>ip_frag_init</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588788237,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785552,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589011146,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009152,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589971784,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:646",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967344,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590012334,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:653",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590007904,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589926702,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:654",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589922080,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590693630,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:641",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590688656,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592321573,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:641",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592316128,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594158565,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:641",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594152944,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594546054,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:643",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594540256,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595348643,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:644",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595342848,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502623200,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502614952,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235324196,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235321360,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296212388,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296209648,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278766746,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278764758,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588617530,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615536,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588329514,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327520,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589053706,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051712,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state * state)
```

```json
{
  "name": "ip_frag_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589092890,
      "name": "ip_frag_init",
      "external": true,
      "loc": "net/ipv4/ip_output.c:647",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090896,
      "name": "ip_frag_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void ip_frag_init(struct sk_buff * skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, struct ip_frag_state * state)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool DF</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, hlen, ll_rs, mtu, state</code> ➡️ <code>skb, hlen, ll_rs, mtu, DF, state</code>
</li>
</ul>
</details>
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
