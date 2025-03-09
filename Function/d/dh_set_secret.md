# Function: <code>dh_set_secret</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060096,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:82",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060096,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226368,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:70",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226368,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434368,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:70",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434368,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583555504,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:78",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555504,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744720,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744720,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854464,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854464,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244768,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244768,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584363456,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:75",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363456,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397856,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:75",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397856,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584793088,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:75",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793088,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585480112,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:71",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480112,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586241456,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:71",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241456,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586481184,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:71",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586481184,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586751120,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:71",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586751120,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495670880,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495670880,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229023264,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229023264,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289810592,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289810592,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274821274,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274821274,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823200,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823200,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760256,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760256,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806960,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806960,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```

```json
{
  "name": "dh_set_secret",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583908032,
      "name": "dh_set_secret",
      "external": false,
      "loc": "crypto/dh.c:74",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908032,
      "name": "dh_set_secret",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int dh_set_secret(struct crypto_kpp * tfm, const void * buf, unsigned int len)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
