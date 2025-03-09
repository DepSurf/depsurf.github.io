# Function: <code>utf8hangul</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583055945,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583162361,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
utf8leaf_t * utf8hangul(const char * str, unsigned char * hangul)
```

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583484688,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484688,
      "name": "utf8hangul",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
utf8leaf_t * utf8hangul(const char * str, unsigned char * hangul)
```

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583592944,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592944,
      "name": "utf8hangul",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583616237,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583974765,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584557574,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:258",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585234790,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:258",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585464374,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:258",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585699350,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:258",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494874596,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228290456,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288732924,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274193058,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583131097,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583068249,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utf8hangul",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208889,
      "name": "utf8hangul",
      "external": false,
      "loc": "fs/unicode/utf8-norm.c:275",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8nlookup"
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
utf8leaf_t * utf8hangul(const char * str, unsigned char * hangul)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
utf8leaf_t * utf8hangul(const char * str, unsigned char * hangul)
```
</details>
</li>
</ul>
