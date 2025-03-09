# Function: <code>mptcp_established_options_add_addr</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591183024,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:591",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183024,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591119408,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:617",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591119408,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:644",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591965616,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071592754085,
      "name": "mptcp_established_options_add_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:646",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593693968,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    },
    {
      "addr": 18446744071594641187,
      "name": "mptcp_established_options_add_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:651",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595627360,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    },
    {
      "addr": 18446744071596370610,
      "name": "mptcp_established_options_add_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:648",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596135664,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071596899871,
      "name": "mptcp_established_options_add_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```

```json
{
  "name": "mptcp_established_options_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_established_options_add_addr",
      "external": false,
      "loc": "net/mptcp/options.c:649",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597009376,
      "name": "mptcp_established_options_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071597825172,
      "name": "mptcp_established_options_add_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool mptcp_established_options_add_addr(struct sock * sk, struct sk_buff * skb, unsigned int * size, unsigned int remaining, struct mptcp_out_options * opts)
```
</details>
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
