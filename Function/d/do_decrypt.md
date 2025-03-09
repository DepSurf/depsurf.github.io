# Function: <code>do_decrypt</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```

```json
{
  "name": "do_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046560,
      "name": "do_decrypt",
      "external": false,
      "loc": "crypto/xts.c:301",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:decrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046560,
      "name": "do_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```

```json
{
  "name": "do_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100784,
      "name": "do_decrypt",
      "external": false,
      "loc": "crypto/xts.c:312",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:decrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100784,
      "name": "do_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```

```json
{
  "name": "do_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267392,
      "name": "do_decrypt",
      "external": false,
      "loc": "crypto/xts.c:310",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:decrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267392,
      "name": "do_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```

```json
{
  "name": "do_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474528,
      "name": "do_decrypt",
      "external": false,
      "loc": "crypto/xts.c:310",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:decrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474528,
      "name": "do_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int do_decrypt(struct skcipher_request * req, int err)
```
</details>
</li>
</ul>
