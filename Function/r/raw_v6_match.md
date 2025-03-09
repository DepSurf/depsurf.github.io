# Function: <code>raw_v6_match</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool raw_v6_match(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "raw_v6_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593246960,
      "name": "raw_v6_match",
      "external": true,
      "loc": "net/ipv6/raw.c:67",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593246960,
      "name": "raw_v6_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
bool raw_v6_match(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "raw_v6_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595148048,
      "name": "raw_v6_match",
      "external": true,
      "loc": "net/ipv6/raw.c:67",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595148048,
      "name": "raw_v6_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
bool raw_v6_match(struct net * net, const struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "raw_v6_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595543264,
      "name": "raw_v6_match",
      "external": true,
      "loc": "net/ipv6/raw.c:67",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595543264,
      "name": "raw_v6_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
bool raw_v6_match(struct net * net, const struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "raw_v6_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596386016,
      "name": "raw_v6_match",
      "external": true,
      "loc": "net/ipv6/raw.c:67",
      "file": "net/ipv6/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596386016,
      "name": "raw_v6_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool raw_v6_match(struct net * net, struct sock * sk, short unsigned int num, const struct in6_addr * loc_addr, const struct in6_addr * rmt_addr, int dif, int sdif)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock * sk</code> ➡️ <code>const struct sock * sk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
