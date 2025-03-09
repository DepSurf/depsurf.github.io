# Function: <code>bpf_sk_storage_diag_put</code>

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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730240,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:1118",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730240,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589765280,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:656",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589765280,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668576,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:656",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668576,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590424912,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:655",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590424912,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592024096,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:666",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592024096,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593840096,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:636",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840096,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594214656,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:634",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214656,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
```

```json
{
  "name": "bpf_sk_storage_diag_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595012032,
      "name": "bpf_sk_storage_diag_put",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:635",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595012032,
      "name": "bpf_sk_storage_diag_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag * diag, struct sock * sk, struct sk_buff * skb, int stg_array_type, unsigned int * res_diag_size)
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
