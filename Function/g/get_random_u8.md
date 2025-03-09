# Function: <code>get_random_u8</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u8 get_random_u8()
```

```json
{
  "name": "get_random_u8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589934960,
      "name": "get_random_u8",
      "external": true,
      "loc": "drivers/char/random.c:530",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_guarded_alloc",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934960,
      "name": "get_random_u8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
u8 get_random_u8()
```

```json
{
  "name": "get_random_u8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590244960,
      "name": "get_random_u8",
      "external": true,
      "loc": "drivers/char/random.c:530",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_rotate_memcg",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244960,
      "name": "get_random_u8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
u8 get_random_u8()
```

```json
{
  "name": "get_random_u8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590585984,
      "name": "get_random_u8",
      "external": true,
      "loc": "drivers/char/random.c:530",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_rotate_memcg",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585984,
      "name": "get_random_u8",
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
u8 get_random_u8()
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
