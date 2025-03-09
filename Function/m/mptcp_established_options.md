# Function: <code>mptcp_established_options</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591104528,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:618",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591104528,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591185776,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:685",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185776,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591121904,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:734",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591121904,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:795",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754686,
      "name": "mptcp_established_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591968768,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:819",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641712,
      "name": "mptcp_established_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593697712,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:824",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371103,
      "name": "mptcp_established_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595631344,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:824",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900417,
      "name": "mptcp_established_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071596139696,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options",
      "external": true,
      "loc": "net/mptcp/options.c:825",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825623,
      "name": "mptcp_established_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071597013408,
      "name": "mptcp_established_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool mptcp_established_options(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```
</details>
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
