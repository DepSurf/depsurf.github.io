# Function: <code>dh_is_pubkey_valid</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583555886,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:113",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583745101,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583854845,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
int dh_is_pubkey_valid(struct dh_ctx * ctx, MPI y)
```

```json
{
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244272,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244272,
      "name": "dh_is_pubkey_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int dh_is_pubkey_valid(struct dh_ctx * ctx, MPI y)
```

```json
{
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584362960,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:110",
      "file": "crypto/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362960,
      "name": "dh_is_pubkey_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584397533,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:110",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584792765,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:110",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585479890,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:107",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586241218,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:107",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586480946,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:107",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586750882,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:107",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495671288,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229022944,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289811140,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274821596,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583823581,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583760637,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583807341,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
  "name": "dh_is_pubkey_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583908413,
      "name": "dh_is_pubkey_valid",
      "external": false,
      "loc": "crypto/dh.c:109",
      "file": "crypto/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh.c:dh_compute_value"
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
int dh_is_pubkey_valid(struct dh_ctx * ctx, MPI y)
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
int dh_is_pubkey_valid(struct dh_ctx * ctx, MPI y)
```
</details>
</li>
</ul>
