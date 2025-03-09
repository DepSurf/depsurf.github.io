# Function: <code>cipher_crypt_one</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:58",
      "file": "crypto/cipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:58",
      "file": "crypto/cipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src, bool enc)
```

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205136,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205136,
      "name": "cipher_crypt_one",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src, bool enc)
```

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443424,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443424,
      "name": "cipher_crypt_one",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src, bool enc)
```

```json
{
  "name": "cipher_crypt_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709280,
      "name": "cipher_crypt_one",
      "external": false,
      "loc": "crypto/cipher.c:59",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cipher.c:crypto_cipher_decrypt_one",
        "crypto/cipher.c:crypto_cipher_encrypt_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709280,
      "name": "cipher_crypt_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void cipher_crypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src, bool enc)
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
