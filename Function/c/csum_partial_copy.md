# Function: <code>csum_partial_copy</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
__wsum csum_partial_copy(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496325328,
      "name": "csum_partial_copy",
      "external": true,
      "loc": "lib/checksum.c:172",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496325328,
      "name": "csum_partial_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__wsum csum_partial_copy(const void * src, void * dst, int len, __wsum sum)
```

```json
{
  "name": "csum_partial_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275377256,
      "name": "csum_partial_copy",
      "external": true,
      "loc": "lib/checksum.c:172",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/ipv4/ip_output.c:ip_reply_glue_bits",
        "net/ipv4/raw.c:raw_getfrag",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv6/raw.c:raw6_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275377256,
      "name": "csum_partial_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
__wsum csum_partial_copy(const void * src, void * dst, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
__wsum csum_partial_copy(const void * src, void * dst, int len, __wsum sum)
```
</details>
</li>
</ul>
