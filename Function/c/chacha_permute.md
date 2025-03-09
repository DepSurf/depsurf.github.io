# Function: <code>chacha_permute</code>

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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589358672,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:19",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358672,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815744,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815744,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590042064,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042064,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688128,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688128,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805776,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805776,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584850304,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850304,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585270544,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270544,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586114832,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114832,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101392,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101392,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361360,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361360,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647952,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/crypto/chacha.c:16",
      "file": "lib/crypto/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/chacha.c:hchacha_block_generic",
        "lib/crypto/chacha.c:chacha_block_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647952,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503803056,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503803056,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236425572,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236425572,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297641216,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297641216,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279700082,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279700082,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644320,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644320,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370192,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370192,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590087696,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087696,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
```

```json
{
  "name": "chacha_permute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590137952,
      "name": "chacha_permute",
      "external": false,
      "loc": "lib/chacha.c:15",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/chacha.c:hchacha_block",
        "lib/chacha.c:chacha_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137952,
      "name": "chacha_permute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void chacha_permute(u32 * x, int nrounds)
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
