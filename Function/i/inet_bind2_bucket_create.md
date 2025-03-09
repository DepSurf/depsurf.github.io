# Function: <code>inet_bind2_bucket_create</code>

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
struct inet_bind2_bucket * inet_bind2_bucket_create(struct kmem_cache * cachep, struct net * net, struct inet_bind_hashbucket * head, short unsigned int port, int l3mdev, const struct sock * sk)
```

```json
{
  "name": "inet_bind2_bucket_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594202739,
      "name": "inet_bind2_bucket_create",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:123",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594195488,
      "name": "inet_bind2_bucket_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct inet_bind2_bucket * inet_bind2_bucket_create(struct kmem_cache * cachep, struct net * net, struct inet_bind_hashbucket * head, short unsigned int port, int l3mdev, const struct sock * sk)
```

```json
{
  "name": "inet_bind2_bucket_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594589690,
      "name": "inet_bind2_bucket_create",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:123",
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
      "addr": 18446744071594582688,
      "name": "inet_bind2_bucket_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct inet_bind2_bucket * inet_bind2_bucket_create(struct kmem_cache * cachep, struct net * net, struct inet_bind_hashbucket * head, struct inet_bind_bucket * tb, const struct sock * sk)
```

```json
{
  "name": "inet_bind2_bucket_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595385696,
      "name": "inet_bind2_bucket_create",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:129",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595385696,
      "name": "inet_bind2_bucket_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct inet_bind2_bucket * inet_bind2_bucket_create(struct kmem_cache * cachep, struct net * net, struct inet_bind_hashbucket * head, short unsigned int port, int l3mdev, const struct sock * sk)
```
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
<b>Param added. </b>
<code>struct inet_bind_bucket * tb</code>
</li>
<li>
<b>Param removed. </b>
<code>short unsigned int port</code>
</li>
<li>
<b>Param removed. </b>
<code>int l3mdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>cachep, net, head, port, l3mdev, sk</code> ➡️ <code>cachep, net, head, tb, sk</code>
</li>
</ul>
</details>
</li>
</ul>
