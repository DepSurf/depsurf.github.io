# Function: <code>__skb_datagram_iter</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587908896,
      "name": "__skb_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:411",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908896,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213904,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    },
    {
      "addr": 18446744071588217969,
      "name": "__skb_datagram_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418624,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418624,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287360,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:412",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287360,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286016,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:412",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286016,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589179920,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:412",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179920,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589898384,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:412",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589898384,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591427728,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:409",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591427728,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593194112,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:406",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593194112,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593653360,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:406",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593653360,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594429216,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:407",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594429216,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501934784,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501934784,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234692716,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234692716,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295355248,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295355248,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278243650,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278243650,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025408,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025408,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738496,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738496,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588357184,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357184,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```

```json
{
  "name": "__skb_datagram_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492768,
      "name": "__skb_datagram_iter",
      "external": false,
      "loc": "net/core/datagram.c:410",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_hash_datagram_iter",
        "net/core/datagram.c:__skb_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492768,
      "name": "__skb_datagram_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __skb_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len, bool fault_short, size_t (*)(const void *, size_t, void *, struct iov_iter *) cb, void * data)
```
</details>
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
