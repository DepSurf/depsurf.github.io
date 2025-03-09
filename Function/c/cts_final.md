# Function: <code>cts_final</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884128,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884128,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274080,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:157",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:encrypt",
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274080,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    }
  ]
}
```
</details>
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495702616,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495702616,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229056584,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229056584,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289851168,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289851168,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274851882,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274851882,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852864,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852864,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583789920,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789920,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583836624,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836624,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```

```json
{
  "name": "cts_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937696,
      "name": "cts_final",
      "external": false,
      "loc": "crypto/xts.c:163",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt_done",
        "crypto/xts.c:encrypt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937696,
      "name": "cts_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int cts_final(struct skcipher_request * req, int (*)(struct skcipher_request *) crypt)
```
</details>
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
