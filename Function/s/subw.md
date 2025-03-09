# Function: <code>subw</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584279084,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689072,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689072,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806752,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806752,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851328,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851328,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271600,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271600,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115920,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115920,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587102528,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587102528,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587362496,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362496,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
u32 subw(u32 in)
```

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587649088,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649088,
      "name": "subw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496164788,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229487908,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290429888,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275215844,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584247820,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584183020,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584231580,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "subw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584336412,
      "name": "subw",
      "external": false,
      "loc": "lib/crypto/aes.c:163",
      "file": "lib/crypto/aes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/aes.c:aes_expandkey",
        "lib/crypto/aes.c:aes_expandkey"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u32 subw(u32 in)
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
