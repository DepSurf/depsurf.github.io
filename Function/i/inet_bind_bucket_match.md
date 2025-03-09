# Function: <code>inet_bind_bucket_match</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_bind_bucket_match(const struct inet_bind_bucket * tb, const struct net * net, short unsigned int port, int l3mdev)
```

```json
{
  "name": "inet_bind_bucket_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594201878,
      "name": "inet_bind_bucket_match",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:95",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594195408,
      "name": "inet_bind_bucket_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool inet_bind_bucket_match(const struct inet_bind_bucket * tb, const struct net * net, short unsigned int port, int l3mdev)
```

```json
{
  "name": "inet_bind_bucket_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594588837,
      "name": "inet_bind_bucket_match",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:95",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594582608,
      "name": "inet_bind_bucket_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool inet_bind_bucket_match(const struct inet_bind_bucket * tb, const struct net * net, short unsigned int port, int l3mdev)
```

```json
{
  "name": "inet_bind_bucket_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595392339,
      "name": "inet_bind_bucket_match",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:96",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595385616,
      "name": "inet_bind_bucket_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool inet_bind_bucket_match(const struct inet_bind_bucket * tb, const struct net * net, short unsigned int port, int l3mdev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
